![CSUEB Logo](/Images/csueb-logo.jpg)

# BaysBook - Cal State East Bay's very own social media platform

<h1 align="center">
🌐 A MERN Stack Web Application
</h1>

> MERN is a fullstack implementation in MongoDB, Expressjs, React/Redux, Nodejs.

## Prerequirements

- [MongoDB](https://gist.github.com/nrollr/9f523ae17ecdbb50311980503409aeb3)
- [Node](https://nodejs.org/en/download/) ^10.0.0
- [npm](https://nodejs.org/en/download/package-manager/)

## Clone or download

```terminal
$ git clone https://gitlab.com/software-engineering4/baysbook.git
$ npm i
```

## Running the application on your machine

- After cloning the repo for this project, first run the following command to cd into the root

```terminal
$ cd s2020-ctrlaltelite
```

- from here, package.json contains all the dependencies to run the app, however, they need to be configured locally so in the terminal, first run the following

```terminal
$ npm install
```

- the dependencies for the backend are now configured. From here, in order to run the front end on the server, do the following:

```terminal
$ cd client
$ npm install
```

- you have successfully installed your configurations locally and our node scripts should work. do the following and then the project should automtically open in your default browser. Notice cd .. this means you are going out one directory and back into the project root, where both client side and backend side code live. We can now run the app! Enjoy your experience on Baysbook!

```terminal
$ cd ..
$ npm run-dev
```

## Project structure

```terminal
LICENSE
package.json
server/
   package.json
client/
   package.json
...
```
