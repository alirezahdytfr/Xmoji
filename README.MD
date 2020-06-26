<div align="center">
  <br><b>Xmoji</b> is a customizable Cross-Platform<br>emoji picker for your OS like emoji panel in MacOS.
  <br>
  
  <br><br><img width="100%" alt="picker" src="https://github.com/Aslemammad/Xmoji/blob/master/github.png?raw=true">
  <br>
  <br>Inspired by <a title="Team email, team chat, team tasks, one app" href="https://github.com/missive/emoji-mart">Emoji mart</a> React component
</div>
<br>
😮❗Select one or multiple emojis, then you'll find out they are automatically in your clipboard.
## Installation

```bash
git clone https://github.com/Aslemammad/Xmoji
```

## Build

first You need to install the npm packages:
<br>

```bash
npm install .
```

<br>
We need to rebuild robotjs:<br>

```bash
npm rebuild --runtime=electron --target=9.0.5 --disturl=https://atom.io/download/atom-shell --abi=83
```

<br>
**Note:** the `target` is the electron version that we use, and the abi is the abi version of the node we have,I have node 14.0.0 so we have `abi=83`.
if You need another node version, You can see the 
<a href='https://github.com/mapbox/node-pre-gyp/blob/master/lib/util/abi_crosswalk.json'>Abi</a> versions here.<br>
The next step is building our project, so: <br>

```bash
npm run full-build
```

<br>Then run the project and mark the <i>Add to startup</i> option.
<br>🎉Congratulations, You have emoji picker in your OS.

**Tip:** Someday if you built the project with `electron builder` or `electron packager`, You should unmark the <i>Add to startup</i> option, and Then add the executable file to your startup.

## Development

If you want to start the project as dev:<br>

```bash
npm run dev
```

## 🎩 Tools

- React
- Electron
- Emoji Mart
- ...

## ❤️ Thanks

Special thanks for contributing and using this project.