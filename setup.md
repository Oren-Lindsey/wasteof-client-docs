# Setup
To install, run `npm i wasteof-client`

## import
Version 3 uses es6 imports instead of `require`. In vanilla node, this means you to include `"type":"module"` in your package.json file

to import: `import { Wasteof2, Wasteof2Auth, Wasteof3 } from 'wasteof-client'`

There are 3 classes you can import:

- [`Wasteof2`](https://oren-lindsey.github.com/wasteof-client-docs/wasteof2): methods that use the wasteof2 server logged out, like getting data. This requires no authentication
- [`Wasteof2Auth`](https://oren-lindsey.github.com/wasteof-client-docs/wasteof2auth): methods using the wasteof2 logged in, like posting and listening to the websocket. This probably includes more useful methods than the other classes
- [`Wasteof3`](https://oren-lindsey.github.com/wasteof-client-docs/wasteof3): methods using the wasteof3 sveltekit server. These are in beta and could change, but wasteof3 sends richer data than wasteof2 so i included it anyways. This class does not require auth

## async 
all methods are asynchronous except a couple like the socket.io things