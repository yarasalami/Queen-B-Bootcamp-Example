# Queen-B-Bootcamp-Example
An example app for the queenB Initiative - Boilerplate

### In order to create a project from this example, please follow the instructions below.


## Prerequisites

* install git - https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
* install docker - in order to run a local postgres database - https://docs.docker.com/get-docker/
* install node.js - https://phoenixnap.com/kb/install-node-js-npm-on-windows
* install npm - package manager


## Running locally

The current configuration runs by the server serving the client code. It is also possible to run both client and server without the server serving the client.
If you wish to tun the client you to do this by running 'npm start' from the client directory.

### Get the boilerplate project

1. Create your own github user, you can connect to it with user password or create an ssh key (configuration - https://github.com/settings/profile)

2. Fork this project to your repository (creates a copy)

3. Clone it to your local computer (downloads the project)

```
$ git clone https://github.com/<you user name>/Queen-B-Bootcamp-Example.git (you can get link for the project)
```

### Client side 

1. open a terminal and cd to the client
```
$ cd client
```
2. add dependencies:

```
$ npm install
```

3. Build the client, in the package.json file there's a command called build, this command will run it

```
$ npm run build 
```

### Server side 
1. open another terminal in the project root

3. add dependencies:

```
$ npm install
```

3. Run the server 

```
$ npm start
```

4. You can run the server while detecting changes in the server side (the application will update)

```
$ npm dev
```


