# igloos--inuit.css plugins

## What?

An igloo is simply a plugin for the [inuit.css](http://inuitcss.com) framework. They extend and add to the the core functionality.

## How?

Include inuit.css in the `&lt;head&gt;` using a `&lt;link /&gt;`, then include igloos in the same manner after this. E.g.

    `&lt;link rel=&quot;stylesheet&quot; href=&quot;/css/inuit.css&quot; /&gt;`
    `&lt;link rel=&quot;stylesheet&quot; href=&quot;/css/annotate.inuit.css&quot; /&gt;`

### HTTP requests?

I am aware of the issues here with several HTTP requests for CSS files, but in order to keep the core framework untouched an updatable we can't combine the CSS into one large document.