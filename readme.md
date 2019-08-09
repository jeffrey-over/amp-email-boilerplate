# AMP Email boilerplate

## Boilerplate
```
<!doctype html>
<html ⚡4email>
<head>
  <meta charset="utf-8">
  <script async src="https://cdn.ampproject.org/v0.js"></script>
  <style amp4email-boilerplate>body{visibility:hidden}</style>
  <style amp-custom>
    h1 {
      margin: 1rem;
    }
  </style>
</head>
<body>
  <h1>Hello, I am an AMP EMAIL!</h1>
</body>
</html>
```

## Elements

### Dynamic Content

| Element | Description |
| ------- | ----------- |
| [`<amp-form>`](https://amp.dev/documentation/components/amp-form) | Form element. The action-xhr attribute must be used in place of the regular action attribute. Can be used in conjunction with `<template type="amp-mustache">` to render a response. |
| [`<amp-selector>`](https://amp.dev/documentation/components/amp-selector) | A multi-select widget for use within a form. |
| [`amp-bind`](https://amp.dev/documentation/components/amp-bind) and [`<amp-bind-macro>`](https://amp.dev/documentation/components/amp-bind#defining-macros-with-amp-bind-macro) | Simple scripting language in AMP that allows the manipulation of a state machine for interactions between elements. Can also be used to add behavior on certain events.<br><br>**Note:** It is prohibited to bind to `[href]` or `[src]`. It is also prohibited to use the `AMP.print`, `AMP.navigateTo` and `AMP.goBack` actions. |
| [`<amp-state>`](https://amp.dev/documentation/components/amp-bind#%3Camp-state%3E-specification) | `<amp-state>` is used to define the initial state used by `amp-bind`.<br><br>**Note:** The `src` attribute is not currently supported. |
| [`<amp-list>`](https://amp.dev/documentation/components/amp-list) | Remotely fetches JSON data that will be rendered by an [`<amp-mustache>`](https://amp.dev/documentation/components/amp-mustache).<br><br>**Note:** Binding to the `[src]` attribute is not allowed. Including user credentials with `credentials="include"` is also prohibited. |
| [`<template type="amp-mustache">`](https://amp.dev/documentation/components/amp-mustache) | A Mustache template markup to render the results of an `amp-list` call. |

### Layout

| Element | Description |
| ------- | ----------- |
| [layout attributes](https://amp.dev/documentation/guides-and-tutorials/learn/amp-html-layout/#layout-attributes)| Layout behavior is determined by the layout attribute. |
| [`<amp-accordion>`](https://amp.dev/documentation/components/amp-accordion)| A UI element that facilitates showing/hiding different sections. |
| [`<amp-carousel>`](https://amp.dev/documentation/components/amp-carousel) | A carousel UI component. |
| [`<amp-fit-text>`](https://amp.dev/documentation/components/amp-fit-text) | A helper component for fitting text within a certain area. |
| [`<amp-layout>`](https://amp.dev/documentation/components/amp-layout) | A container that can have aspect-ratio based responsive layouts. |
| [`<amp-sidebar>`](https://amp.dev/documentation/components/amp-sidebar) | A sidebar for navigational purposes. |
| [`<amp-timeago>`](https://amp.dev/documentation/components/amp-timeago) | Provides a convenient way of rendering timestamps. |

### Media

| Element | Description |
| ------- | ----------- |
| [`<amp-img>`](https://amp.dev/documentation/components/amp-img) | An AMP component that replaces `<img>`.<br><br>**Note:** Binding to `[src]` is not allowed. |
| [`<amp-anim>`](https://amp.dev/documentation/components/amp-anim) | Embeds GIF files.<br><br>**Note:** Binding to `[src]` is not allowed. |

## Sandbox
- https://amp.gmail.dev/playground/

### Sources
- https://amp.dev
- https://ampproject.org
- https://www.sparkpost.com
