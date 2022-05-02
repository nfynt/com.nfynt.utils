# com.nfynt.utils
[![npm version](https://badge.fury.io/js/com.nfynt.utils.svg)](https://badge.fury.io/js/com.nfynt.utils)

### Utility Package for Unity
Collection of plugins, scripts, and assets to aid in Unity development within editor or at runtime. List of features and functions include:
- Anchoring of canvas UI elements to corner w.r.t. RectTransform (shortcut: `%(Ctrl/Cmd) + U`).
- Debug individual mesh filter properties attached to a gameobject (Context menu `Nfynt > Mesh filter stats`).
- PC and mobile friendly full-screen WebGL template (Player > Resolution and Presentation - `NFYNT`).
- Fix Unity InputField component for WebGL builds (including mobile). Simply add `WebGLInput` script to your InputField gameobject in scene.

### Importing in Unity

To install this package in Unity you'll first have to add a new Scoped Registry. Head over to `Edit>Project Settings>Package Manager` and add the new registry details as follows - 
```
Name: npmjs
URL: https://registry.npmjs.org
Scope(s): com.nfynt
```

After this head to `Window>Package Manager` and select `My Registries` under the `Packages:` options. This will list all the available package on npm, find `NFYNT utils` and select the latest version available and hit install 🚀.

### Issues
Submit issues on [Github Repo](https://github.com/nfynt/com.nfynt.utils/issues) with appropriate label as `bug\enhancement\help wanted`.

### Authors
```
Shubham
```
