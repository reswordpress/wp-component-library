---
title: Off Canvas Menu
path_slug: menu-dropdown
layout: component
category: navigation
---

<h2>{{page.title}}</h2>

{% include_relative _notes.md %}

<iframe src="{{ site.baseurl}}/component/{{ page.path_slug }}/example.html"></iframe>

<h3>HTML</h3>

```html
{% include_relative component.html %}
```

<h3>SCSS</h3>

```scss
{% include_relative scss/component.scss %}
```

<h3>JS</h3>

```javascript
{% include_relative component.js %}
```

<h3>Resources</h3>

{% include_relative _resources.md %}