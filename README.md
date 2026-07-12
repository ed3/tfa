# TinyMCE Font Awesome

Font Awesome plugin for TinyMCE.

![Font Awesome](/tfa.png)

Requirement
---

- [TinyMCE](https://www.tiny.cloud) 7.x
- [Font Awesome](https://fontawesome.com) 6.7.2


Configuration
---

- Create folder `tfa` into the TinyMCE `plugins` folder.

- Add to init:

```js
tinymce.init({
...
content_css:'/css/all.min.css',
extended_valid_elements:'#span[*]'
...
});
```

- add to plugins `tfa` and to toolbar/menubar `tfa`
