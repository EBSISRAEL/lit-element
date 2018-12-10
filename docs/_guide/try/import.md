---
layout: post
section: try
topic: import
---

Import your new component as a JavaScript module and use it in a web page.

**Starting code**

_index.html_

```html
{% include projects/try/import/before/index.html %}
```

{% include project.html folder="try/import/before" openFile="index.html" %}

1. **Import your component module.** 

    LitElement components are imported as JavaScript modules. **You don't need to change anything in this step if you're following the tutorial in StackBlitz**. In StackBlitz, index.ts runs automatically.

    _index.ts_

    ```js
    {% include projects/try/import/after/index.ts %}
    ```

    If you're working locally, see [Import a LitElement component](/docs/create/#import).

2. **Add your new component to the page.** 

    In index.html, replace the existing `body` block with the following code:

    ```html
      <body>
        <my-element></my-element>
      </body>
    ```

If you're stuck, click **Launch Code Editor** below to see the completed code at work. 

{% include project.html folder="try/import/after" openFile="index.html" %}

{% include prevnext.html prevurl="create" prevtitle="1. Create" nexturl="properties" nexttitle="3. Properties" %}
