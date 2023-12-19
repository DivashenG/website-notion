# website-notion
[![pages-build-deployment](https://github.com/DivashenG/website-notion/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/DivashenG/website-notion/actions/workflows/pages/pages-build-deployment)

### Customise Emoji Size
```scss
<style type="text/css">
/* Adjust the size of Jemoji emojis */
img.emoji {
    width: 35px; /* Set the desired width */
    height: auto; /* Maintain aspect ratio */
}
</style>
```

## Debugging
```markdown
<pre>
    site: {{ site | jsonify | escape }}
    page: {{ page | jsonify | escape }}
    layout: {{ layout | jsonify | escape }}
    content: {{ content | jsonify | escape }}
    paginator: {{ paginator | jsonify | escape }}
</pre>
```
