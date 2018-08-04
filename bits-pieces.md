---
title: "Bits & Pieces"
permalink: "/bits-pieces/"
layout: page
order: 2
date: 2018-08-03 14:13:49 -0600
---
Here is an incomplete list of tools I use most everyday and why:

1. [Code](https://code.visualstudio.com/) - This is becoming my weapon of choice when writing in JavaScript, CFML, and Markdown.  I use the following plugins:
  *Beautify by HookyQR
  *ESLint by Dirk Baeumer
  *Prettier - Code formatter by Esben Petersen
  *Coldfusion (CFML Language Support) by Llya Verbinsky
  *Ocean-Dark-Soda Theme by Gerene

For writing JavaScript, I've further customized my setup with these settings to take advantage of autoformating features of these plugins.
```
{
  // Controls the font size.
  "editor.fontSize": 14,
  "editor.insertSpaces": false,
  "editor.renderIndentGuides": false,
  "workbench.colorTheme": "Ocean-Dark-Soda",
  "extensions.ignoreRecommendations": false,
  "editor.formatOnSave": true,
  "[javascript]": {
    "editor.formatOnSave": false
  },
  "eslint.autoFixOnSave": true,
  "eslint.alwaysShowStatus": true,
  "prettier.disableLanguages": [
    "js"
  ],
  "files.autoSave": "onFocusChange",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "window.zoomLevel": 0,
}
```


2. [Atom](https://atom.io/) - I uses on and off for years, and now it acts as a backup when I am toggling between two languages.  For example, if I'm in the middle of an issue in one project using VS Code, then I will use Atom to address something in a different project without interupting my flow.  I'm also fond of the XML formatter package by Neyestrabelli for formatting cXML documents from the SAP Arbiba Network.
3. [BBEdit](https://www.barebones.com/products/bbedit/) - As they say, "It doesn't suck," and after TextWrangler went away this has become my Swiss Army Knife of editors.  I use it for zapping gremlins and I especially like their built in open from SFTP functionality for working on remote servers.  This is just one of those programs that once you starting using it, you can't stop. 
4. [Postman](https://www.getpostman.com/) - God bless the people that created this program.  If you work with APIs this is the tool you use, full stop.
5. [Navicat](https://navicat.com/en) - I do a lot of work with MySQL and this is a program I've used for the past 10 years or so.  Of all the tools here, this is the one I am looking to replace because as my save queries have grown, they are difficult to organize and manage within the tool.  So I've started to play with MySQL Workbench & SQL Pro, but haven't made the leap.
6. [iTerm2](https://iterm2.com/) - I saw a video by  Wes Bos on pimping the terminal a couple of years ago and never looked back [Pimp your terminal with Custom ZSH Themes & Prompts](https://www.youtube.com/watch?v=XSeO6nnlWHw)
