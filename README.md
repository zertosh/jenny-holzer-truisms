Jenny Holzer: Truisms
=======================

#### Usage

```bash
curl -s https://raw.githubusercontent.com/zertosh/jenny-holzer-truisms/master/truisms.txt | sort -R | head -n 1
```

#### Source

From https://mfx.dasburo.com/art/truisms.html with:

```js
JSON.stringify(
  [].map.call(
    document.body.querySelectorAll('p'),
    function(el) { return el.textContent; }
  )
)
```

And:

```js
[].map.call(
  document.body.querySelectorAll('p'),
  function(el) { return el.textContent; }
).join('\n')
```
