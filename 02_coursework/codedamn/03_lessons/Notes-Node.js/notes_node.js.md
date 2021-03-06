# INTRODUCTION

**_Node.js_** is an open-source, cross-platform, back-end JavaScript runtime environment that allows developers to build server-side and network applications with JavaScript.

# Module System

Modules are the fundamental building blocks of the code structure. The module system allows you to organize your code, hide information and only expose the public interface of a component using module.exports. Every time you use the require call, you are loading another module. <br> <br>

# ECMAScript 5 module systems

The two most important (and unfortunately incompatible) standards are:

**_CommonJS Modules_**: The dominant implementation of this standard is in Node.js (Node.js modules have a few features that go beyond CommonJS). Characteristics:

- Compact syntax

- Designed for synchronous loading and servers

**_Asynchronous Module Definition (AMD)_**: The most popular implementation of this standard is RequireJS. Characteristics: <br>

- Slightly more complicated syntax, enabling AMD to work without eval() (or a compilation step)

- Designed for asynchronous loading and browsers <br><br>

## COMMON JS

The CommonJS module specification is the standard used in Node.js for working with modules.

The syntax to import a module is:

`const package = require('module-name')`

In CommonJS, modules are loaded synchronously, and processed in the order the JavaScript runtime finds them. This system was born with server-side JavaScript in mind, and is not suitable for the client-side (this is why ES Modules were introduced).

# ECMAScript 6 module system

The goal for ECMAScript 6 modules was to create a format that both users of CommonJS and of AMD are happy with:

- Similarly to CommonJS, they have a compact syntax, a preference for single exports and support for cyclic dependencies.

- Similarly to AMD, they have direct support for asynchronous loading and configurable module loading. <br><br>

Being built into the language allows ES6 modules to go beyond CommonJS and AMD (details are explained later):

- Their syntax is even more compact than CommonJS???s.
- Their structure can be statically analyzed (for static checking, optimization, etc.).
- Their support for cyclic dependencies is better than CommonJS???s. <br><br>

## The ES6 module standard has two parts:

- Declarative syntax (for importing and exporting)

- Programmatic loader API: to configure how modules are loaded and to conditionally load modules

Syntax: <br>

`import package from 'module-name'`

An HTML page can add a module by using a `<script>` tag with the special **_type="module"_** attribute:

`<script type="module" src="index.js"></script>` <br><br>

# CREATING SERVERS

## Creating Server using **_???http??? Module_**:

Import http module: Import http module and store returned HTTP instance into a variable.

**Syntax**:

`var http = require("http");` <br>
Creating and Binding Server: Create a server instance using createServer() method and bind it to some port using listen() method.

**Syntax**:

`const server = http.createServer().listen(port)` <br>
**_Parameter)_**: This method **_(listen())_** accepts a single parameter as mentioned above and described below:

- port <Number>: Ports are in the range _1024 to 65535_ containing both registered and Dynamic ports. <br><br>

## Creating Server using **_???Express??? Module_**:

In order to use the express module, we need to install the **NPM** (_Node Package Manager_) and the following modules (_on cmd_).

// Creates package.json file

> > npm init

// Installs express module

> > npm install express --save OR <br>
> > npm i express -s <br>

**_Import express module_**: Import express module and store returned instance into a variable.

**Syntax**:

`var express = require("express");` <br><br>
**_Creating Server_**: The above syntax calls the **???express()???** function and creates a new express application which gets stored inside the app variable.

**Syntax**:

`const app = express();`  
// OR by Importing and creating express application <br>
`var express = require("express")();` <br>
**_Sending and listening to the response_**: It communicates the request and response with the client and the server. It requires **PORT** `<number>` and **IP** `<number>` to communicate.

`app.listen(PORT, IP, Callback);` <br>
**_Parameter_**: This method accepts three parameters as mentioned above and described below.

- **_PORT_** `<Number>`: Ports are the endpoints of communication which helps to communicate with the client and the server.
- **_IP_** `<Number>`: IPs represent IPv4 or IPv6 address of a host or a device.
- **_Callback_** `<Function>`: It accepts a function.
