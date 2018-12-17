# Full-Stack-DevTools-Setup-Guide

A short setup guide to help people get up to speed quickly with a barebones full-stack setup based on javascript on Mac OSX and above.

## Introduction

Setting up a new computer is probably one of the most dreaded parts about getting a new computer for experienced devs. It can sometimes be difficult to find a good barebones list of required software in order to get started for new and aspiring students as well.

In general there are a few things you need installed globally on your computer in order to get a javascript-based dev environment running. This guide will focus on those items while project-specific tools will not be covered (things like react, webpack, etc).

### Table of Contents

- [Node](#node)
- [Xcode](#Xcode)
- [Homebrew](#homebrew)
- [Editor](#editor)
- [NPM](#npm)
- [Nodemon](#nodemon)
- [Databases](#databases)

---

### Node

Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine. With this tool we are able to take javascript out of the browser and use it to build virtually anything. We can build servers, scripts, and tools that previously were out of reach since Javascript lacked a compiler or general purpose interpreter outside the browser.

[Download Node Here](https://nodejs.org/en/)

---

### Xcode

Xcode is an IDE that ships with all Apple Mac computers. It allows you to build software for all mac devices (MacOS, iOS, WatchOS, and tvOS). Also available but not installed by default are a small package of command line tools that are essential for modern development workflows (including git).

To check if you have this installed run the following command:

> `xcode-select --version`

To install enter the following command into your terminal:

> `xcode-select --install`

---

### Homebrew

Homebrew is used to install and manage software packages and symlink them to /usr/local. You can create your own packages and download packages others have created. Some development tools use Homebrew as their primary installation method so its good to have this setup on your computer in case you want to install one of these later.

To install Homebrew type the following command into your terminal:

> `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

To make sure it is installed correctly type in the following command and follow any troubleshooting tips it provides:

> `brew doctor`

To make sure you are using the latest version of homebrew type this command into the terminal(You should do this every time you want to install a package through homebrew if you haven't used it in a while):

> `brew update`

---

### Editor

Choice of editor is a very personal choice for many developers. Here are some links to whats popular in the industry these days for working in full stack Javascript. In addition, a flavor of vim very likely already exists on your machine if you want to be old school.

1. [Visual Studio Code](https://code.visualstudio.com/)
2. [Sublime Text](https://www.sublimetext.com/)
3. [Atom](https://atom.io/)
4. [Brackets](http://brackets.io/index.html)

---

### NPM

NPM is the package manager for JavaScript and the world’s largest software registry. You use this to share code you've written with others or to search for existing libraries and code to handle a wide variety of common tasks. This is included with node so if you followed the step above you should already have it.

You can check by running the following command in your terminal:

> `npm -v`

---

### Nodemon

Nodemon is a utility that will monitor for any changes in your source code and automatically restart your server. This means you can have the code for your server open and make changes and the server will restart and apply the updates immediately. Very useful for development.

You can install this with npm:

> `npm install -g nodemon`

---

### Databases

Any database you want to use in development generally needs to be installed on your system globally. There are so many databases out there that it is not possible to have a reasonable discussion of what to choose here. Below are a list of some popular databases.

#### Relational DBs

1. [MySQL 8](https://dev.mysql.com/downloads/mysql/)
2. [MySQL 5.7](https://dev.mysql.com/downloads/mysql/5.7.html#downloads)
3. [MariaDB](https://mariadb.com/kb/en/library/installing-mariadb-on-macos-using-homebrew/)
4. [PostgreSQL](https://www.postgresql.org/download/macosx/)

#### Non-Relational DBs

1. [MongoDB](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/#update-homebrew-s-package-database)
2. [CassandraDB](https://gist.github.com/hkhamm/a9a2b45dd749e5d3b3ae)
3. [Neo4j](https://neo4j.com/docs/operations-manual/current/installation/osx/)
4. [Hbase](http://macappstore.org/hbase/)

---
