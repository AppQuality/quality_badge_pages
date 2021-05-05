# quality_badge_pages
## AppQuality Badge Integration Guide 
## HTML
Place this element where you wish the widget to appear
```
<div id="appquality-quality-badge"></div>
```
## JavaScript
Place this JavaScript code before closing of your body tag
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
