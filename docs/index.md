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

Having this element in place, insert the AnnounceKit widget code provided to you in your Widget configuration page.
Note that the widget code contains a placeholder: YOUR_ELEMENT_SELECTOR. You need to set this selector to target the element you created before.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/AppQuality/quality_badge_pages/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
