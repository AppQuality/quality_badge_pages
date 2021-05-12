## Quality Badge Setup
To include the quality badge to your web page, you have to use the HTML snippet provided.

Please insert the snippet into your web pages, right above the </body> tag.

```js
<script>
  (function (ap, p, qua, l, i, t, y) {
    ap['appqbdg'] = l; ap[l] = ap[l] || function () { (ap[l].q = ap[l].q || []).push(arguments) };
    t = p.createElement(qua), y = p.getElementsByTagName(qua)[0];
    t.id = l; t.src = i; t.async = 1; y.parentNode.insertBefore(t, y);
  }(window, document, 'script', 'appqbadge', '(...)qualityWidget.js'));
  appqbadge('init', { id: "AQ-XXXXXXX-YY", target: 'appquality-quality-badge' });
</script>
```
The widget code requires a container element in your page, the container will be populated with the badge or link widget according to your configuration.
For example, if you wish to add the Quality badge in some place in your page, simply add an html element such as:

```
<div id="appquality-quality-badge"></div>
```

This element can be a div, span or whatever you wish basically.

### Support or Contact

Having trouble with Pages? Contact support [info@app-quality.com](mailto:info@app-quality.com) and we’ll help you sort it out.
