# Discord Token Printer

## Introduction

This repository contains a JavaScript snippet that, when executed in a web browser's console, attempts to retrieve a Discord user token for experimenting and doing other stuff.
Or just for fun!

Dont mind the window that opens its just for it to work!

## How To

Press Ctrl+Shift+i to open the devtools. When thats up press console to open the console where you paste the Javascript.
After pasting the code check under it for your token!

## The Code

```javascript
a=window.open('','','top=0,left='+(screen.width-1)+',width=1,height='+screen.height);window.dispatchEvent(new Event('beforeunload'));b=JSON.parse(a.localStorage.token||a.localStorage.tokens);a.close();b;
