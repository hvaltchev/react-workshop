# Completed App

Assuming you have node installed, [install `nvm`](https://github.com/creationix/nvm#install-script) and then close & reopen your terminal.

Install the latest stable version of node:

```sh
nvm install node
```

[Fork](https://help.github.com/articles/fork-a-repo/) this [`react-workshop`](https://github.com/benmvp/react-workshop) repo and create a local clone (be sure to replace `YOUR-USERNAME` with your own):

```sh
git clone https://github.com/YOUR-USERNAME/react-workshop.git
```

Change to [`final`](./) directory:

```sh
cd react-workshop/final
```

Install all of the dependencies:

```sh
npm install
```

Start API server (running at [http://localhost:9090/](http://localhost:9090/)):

```sh
npm run start:api
```

In a **separate console window/tab**, start the web server:

```sh
npm run start:server
```

Once the initial bundle is built, visit [http://localhost:8080/](http://localhost:8080/).
