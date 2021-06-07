# iohook

[![Gitter chat](https://badges.gitter.im/gitterHQ/gitter.png)](https://gitter.im/iohookjs/Lobby)

## About

This is a maintained and updated fork of the original [iohook](https://github.com/wilix-team/iohook) project.

Node.js global native keyboard and mouse listener.

This module can handle keyboard and mouse events via native hooks, inside and outside your JavaScript/TypeScript application.

Found a bug? Have an idea? Feel free to post an [issue](https://github.com/wilix-team/iohook/issues) or submit a [PR](https://github.com/wilix-team/iohook/pulls).

**Check out the [documentation](https://wilix-team.github.io/iohook).**

### Install

```bash
npm install @ash0x0/iohook --save
```
```bash
yarn add @ash0x0/iohook
```

## Platform Support

- Versions >= 0.6.0 support only officially supported platforms versions.
- Versions 0.5.X are the last to support Electron < 4.0.0
- Versions 0.4.X are the last to support for Node < 8.0 and Electron < 2.0.0

### Build (including WSL)

On Linux (including WSL) platform, you will need `libxkbcommon-x11` installed

```bash
sudo apt-get install -y libxkbcommon-x11-0
```

## FAQ

Q. _Does this module require Java ?_

A. No, this module doesn't require Java (like jnativehook) or any other runtimes.

Q. _Is iohook compatible with Node/Electron version X.Y.Z ?_

A. We try to match the currently supported version of both [Node](https://nodejs.org/en/about/releases/) and [Electron](https://electronjs.org/docs/tutorial/support#currently-supported-versions).

## Apps

Are you using iohook in your project ? Please tell us in a [PR](https://github.com/wilix-team/iohook/pulls) so we an add it to the list !

- [Cortex](https://crtx.gg/)
- [Tracklify](https://tracklify.com/)
- [CrewLink](https://github.com/ottomated/CrewLink)
- [Runtime](https://github.com/yikuansun/desktopspeedruntools#runtime-speedrun-tools)

## Contributors

Thanks to _kwhat_ for the [libuiohook](https://github.com/kwhat/libuiohook) project and [ayoubserti](https://github.com/ayoubserti) for the first iohook prototype.

- [vespakoen](https://github.com/vespakoen) (prebuild system implementation)
- [matthewshirley](https://github.com/matthewshirley) (Windows prebuild fix)
- [djiit](https://github.com/djiit) (project & community help)
- [ezain](https://github.com/eboukamza) (add feature enable/disable mouse click propagation)
- [anoadragon453](https://github.com/anoadragon453) (electron 4+ support)
- [ykhwong](https://github.com/ykhwong) (node-gyp usage, electron 9+ support)
- All the other contributors. Feel free to extend this list !
