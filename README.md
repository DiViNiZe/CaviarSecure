# Carviar Secure
An Application for remember password Butiful design Fast working Use React babel redux .Knocking lasspass down.eiei Develop By lowF@Tdeveloper

[![NPM Version][npm-image]][npm-url]
[![NPM Downloads][downloads-image]][downloads-url]

## Installation

This package is available on [npm](https://www.npmjs.com/package/react-chrome-redux):

```
npm install react-chrome-redux
```

## Overview

`react-chrome-redux` allows you to build your Chrome extension like a Redux-powered webapp. The background page holds the Redux store, while Popovers and Content-Scripts act as UI Components, passing actions and state updates between themselves and the background store. At the end of the day, you have a single source of truth (your Redux store) that describes the entire state of your extension.

All UI Components follow the same basic flow:

1. UI Component dispatches action to a Proxy Store.
2. Proxy Store passes action to background script.
3. Redux Store on the background script updates its state and sends it back to UI Component.
4. UI Component is updated with updated state.

![Architecture](https://cloud.githubusercontent.com/assets/603426/18599404/329ca9ca-7c0d-11e6-9a02-5718a0fba8db.png)

## Basic Usage ([full docs here](https://github.com/tshaddix/react-chrome-redux/wiki))

