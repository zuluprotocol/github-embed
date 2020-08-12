# github-embed

Embed GitHub source code into a web-page like a Gist. 

## Features

* Embed GitHub source code file into a web-page
* Display only selected lines passed in query string
* Display dynamic code section using special identifier
* Customisable colour schemes
* Display line numbers

## How to use this script

Host embed.js and 404.html on a web server, or bundle with a local web project. A service like netlify will be ideal.

Visit 404.html in a web browser and configure the GitHub code URL you wish to preview like a gist.

---

Alternatively, host embed.js and use it as follows:

```
<body>
   <script src="./embed.js?target=https%3A%2F%2Fgithub.com%2Fyour-username%2Fyour-repo%2Fblob%2Fmaster%2Fexample.py&style=gradient-dark&hideFileMeta=off"></script>
</body>

```

## Background

This script was adapted from the work by (yusanshi)[https://github.com/yusanshi/embed-like-gist] and altered to match the requirements for embedding code in Vega documentation. It is shared open-source under the MIT license.