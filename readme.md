#js-vim-embed

Embed js-vim on any web page

## Usage

```html
<!DOCYPE html>
<html>
<head>
</head>
<body>
  <div id='vim'></div>
  <script src='/vim.js'></script>
  <script>
    var vim = new Vim({el: document.getElementById('vim')});
  </script>
</body>
</html>
```

## API

```
vim.text(): string  // GET
vim.text(string)    // SET

vim.curDoc.text(): string  // GET
vim.curDoc.text(string)    // SET
```
