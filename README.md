# JS/TS/ReactJS/Redux snippets

This extension provides snippets for JavaScript, TypeScript, ReactJS and Redux which will help you with everyday needs for commands.

![Version](https://vsmarketplacebadge.apphb.com/version-short/lzrnic.javascript-vscode-extension.svg)

![Downloads](https://vsmarketplacebadge.apphb.com/downloads-short/lzrnic.javascript-vscode-extension.svg)

Here is direct link to marketplace [JS/TS/ReactJS/Redux snippets](https://marketplace.visualstudio.com/items?itemName=lzrnic.javascript-vscode-extension)

More snippets will come soon!

## Supported

- JavaScript (.js and .jsx)
- React JS
- TypeScript (.ts and .tsx)
- Redux

## Release Notes

Current version is 1.0.3 [15 Jun 2019]

## Author

Luka Zrnić

## Basic Methods

| Prefix    | Description                                             |
| --------- | ------------------------------------------------------- |
| `csl→`    | Creates default `console.log(value);`                   |
| `cslt→`   | Creates default `console.log('text', value);` with text |
| `func→`   | Creates default function                                |
| `fp1→`    | Creates function with **1** parameter                   |
| `fp2→`    | Creates function with **2** parameters                  |
| `arrf→`   | Creates default arrow function                          |
| `afp1→`   | Creates arrow function with **1** parameter             |
| `afp2→`   | Creates arrow function with **2** parameters            |
| `objC→`   | Creates `const object` with one _name:value_ pair       |
| `objL→`   | Creates `let object` with one _name:value_ pair         |
| `objV→`   | Creates `var object` with one _name:value_ pair         |
| `ifs→`    | Creates _if_ statement                                  |
| `ifel→`   | Creates _if/else_ statement                             |
| `ifelif→` | Creates _if/else if/else_ statement                     |
| `swca→`   | Switch case with _2 cases_                              |
| `floop→`  | Creates default _for_ loop                              |
| `wloop→`  | Creates default _while_ loop                            |
| `dwloop→` | Creates default _do/while_ loop                         |


## Redux

| Prefix   | Description                     |
| -------- | --------------------------------|
| `rdat→`  | Creates `const` for Action type |
| `rdac→`  | Creates Redux Action            |
| `rdr→`   | Creates Redux Reducer           |
| `rdcr→`  | Creates Redux Combine Reducers  |
| `rds→`   | Creates Redux Store             |

### react-redux

| Prefix     | Description                                                         |
| ---------- | ------------------------------------------------------------------- |
| `imrrdc→`  | `import { connect } from 'react-redux';`                            |
| `imrrdp→`  | `import { Provider } from 'react-redux';`                           |
| `mstp→`    | Creates `const mapStateToProps = (state) => { ... }`                |
| `mdtp→`    | Creates `const mapDispatchToProps = (dispatch) => { ... }`          |


## React

| Prefix   | Description                                                             |
| -------- | ----------------------------------------------------------------------- |
| `imr→`   | `import React from 'react';`                                            |
| `imrd→`  | `import ReactDOM from 'react-dom';`                                     |
| `imrc→`  | `import React, { Component } from 'react';`                             |
| `imcc→`  | `import ComponentName from 'ComponentLocation';`                        |
| `imrpc→` | `import React, { PureComponent } from 'react';`                         |
| `cst→`   | `state = { key: value }`                                                |
| `cdm→`   | `componentDidMount = () => { // do something }`                         |
| `cwm→`   | `componentWillMount = () => { // do something }`                        |
| `cwun→`  | `componentWillUnmount = () => { // do something }`                      |
| `cwrp→`  | `componentWillReceiveProps = (nextProps) => { // do something }`        |
| `scup→`  | `shouldComponentUpdate = (nextProps, nextState) => { // do something }` |
| `cwup→`  | `componentWillUpdate = (nextProps, nextState) => { // do something }`   |
| `cdup→`  | `componentDidUpdate = (prevProps, prevState) => { // do something }`    |

## React Components

### `rcc`

```javascript
import React, { Component } from "react";

class CLassName extends Component {
  render() {
    return <div> </div>;
  }
}

export default ClassName;
```

### `rfc`

```javascript
import React from "react";

const ComponentName = () => {
  return <div> </div>;
};

export default ComponentName;
```
