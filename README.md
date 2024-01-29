# Fork from glitchedgitz/codemirror-lang-http

# Http Request/Response Lezer Parser for Codemirror v6

> *Initially created for [GRROXY](https://github.com/glitchedgitz/grroxy)*

### Features
- One parser for request/response
- Auto detect and parse body of request/response
- `Param=value` highlight for URI and Cookies/Set-Cookies 
- Autocomplete Headers and Methods

### Install

```
npm i codemirror-lang-http-bak
```

### Usage
Just push it in your extensions
```js
EditorState.create({
    extensions: [
    // other extensions
    http()
    ],
}),
```


### Supported Body Languages 
`HTML`, `JSON`, `JavaScript`, `JS`, `XML`

### Todo
`GraphQL`



