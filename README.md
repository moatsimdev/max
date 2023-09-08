<div align="center">
	<br/>
	<br/>
	<p>
		<a href="https://discord.gg/tk8GkmeVH7"><img src="https://img.shields.io/discord/1112831968443388037?color=5865F2&logo=discord&logoColor=white" alt="Discord server" /></a>
		<a href="https://www.npmjs.com/package/maxblox.js"><img src="https://img.shields.io/npm/v/maxblox.js.svg?maxAge=3600" alt="npm version" /></a>
		<a href="https://www.npmjs.com/package/maxblox.js"><img src="https://img.shields.io/npm/dt/maxblox.js.svg?maxAge=3600" alt="npm downloads" /></a>
	</p>
</div>

## About 

```maxblox.js``` is a convenient npm library that simplifies the usage of the Roblox API, making it easier for developers to interact with Roblox in their Node.js projects.

## Features

- Simplified and streamlined integration of the Roblox API
- Easy authentication and login process
- Access to various Roblox API endpoints and functionalities

## Installation

```sh
npm install maxblox.js
```

## Import Files

Here's an example of import zoblox.js in your project:

```js
const { Max } = require('maxblox.js');
// If you are using ES6 modules, follow the following code:
import { Max } from 'maxblox.js';
```

## Usage

Here's an example of how to log in and retrieve the username and ID using maxblox.js: 

```js
const max = new Max();

max.on('userReady', () => console.log(`Logged in : ${max.me.username} `));

(async () => {
  await max.login(COOKIE); // Replace COOKIE with your RobloxSecurity
})();
```

## Links
- [maxblox.js Discord server][discord]
- [GitHub][source]
- [npm][npm]

## Help 

If you don't understand something in the documentation, you are experiencing problems, or you just need a gentle nudge in the right direction, please don't hesitate to join our official [maxblox.js Server][discord].

## Developers

- [Moatsim](https://github.com/moatsimdev)

[discord]: https://discord.gg/tk8GkmeVH7
[source]: https://github.com/moatsimdev/maxblox.js
[npm]: https://npmjs.org/package/maxblox.js
