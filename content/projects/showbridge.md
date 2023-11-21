---
title: "showbridge"
date: 2023-06-12T12:00:00-06:00
draft: false
---

## What is it?
[Showbridge](https://github.com/jwetzell/showbridge) is a protocol "router" of sorts that allows the user to take in messages (OSC, MIDI, etc) and perform actions when certain criteria are met. The layout of the application takes HEAVY inspiration from [companion](https://github.com/bitfocus/companion). Instances of the router can also be linked together using a "cloud" server that utilizes [Socket.IO](https://socket.io/) to facilitate message passing.

Some of the technologies are listed below.

* [webui](https://github.com/jwetzell/showbridge/tree/main/webui) - [Demo](https://demo.showbridge.io) - [NPM](https://www.npmjs.com/package/@showbridge/webui)
    * [Angular Material](https://material.angular.io/) (Web UI)
    * [Angular](https://angular.io/) (Web UI)

* [launcher](https://github.com/jwetzell/showbridge/tree/main/launcher)
    * [Electron](https://www.electronjs.org/)
    * [electron-builder](https://www.electron.build/) (package, publish)
    * [ncc](https://github.com/vercel/ncc) (script bundling)

* [lib](https://github.com/jwetzell/showbridge/tree/main/lib) - [NPM](https://www.npmjs.com/package/@showbridge/lib)
    * [Socket.IO](https://socket.io/) ("Cloud" Messaging)
    * [lodash](https://lodash.com/) (string templating)

* [main.js](https://github.com/jwetzell/showbridge) - [NPM](https://www.npmjs.com/package/@showbridge/cli)
    * [commander](https://github.com/tj/commander.js) (CLI)

* [cloud](https://github.com/jwetzell/showbridge/tree/main/cloud) - [Docker](https://hub.docker.com/r/jwetzell/showbridge-cloud) - [NPM](https://www.npmjs.com/package/@showbridge/cloud)
    * [Socket.IO](https://socket.io/) ("Cloud" Messaging)

## Where can I get it?
* [Source](https://github.com/jwetzell/showbridge)
