# Web Components the Right Way

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> This is a guide intended to introduce to Web Components. Everyone can contribute here!

## Contents

- [Specifications](#specifications)
- [Overview](#Overview)
- [Custom Elements](#custom-elements)
- [Shadow DOM](#shadow-dom)
- [HTML Templates](#html-templates)
- [Polyfills](#polyfills)
- [Libraries](#libraries)
- [Best Practices](#best-practices)
- [Blogs](#blogs)
- [Screencasts](#screencasts)
- [Who to follow](#who-to-follow)
- [License](#license)

> Web Components the Right Way was made with love by [Mateus Ortiz](https://twitter.com/mteusortiz)

## Specifications

* [Web Components](http://w3c.github.io/webcomponents/explainer/) — This document is a non-normative reference, which provides an overview of Web Components.
* [Shadow DOM](http://w3c.github.io/webcomponents/spec/shadow/) — Spec of Shadow DOM
* [Template](https://html.spec.whatwg.org/multipage/scripting.html#the-template-element) — Spec of Template
* [Custom Elements](http://w3c.github.io/webcomponents/spec/custom/) — Spec Custom Elements is cherry on cake.

## Overview

* [Understanding Web Components](https://medium.com/the-ui-files/understanding-web-components-d051baa66019) Another overview of web components specs and explanation of their advantages: composability, encapsulation, reusability.
* [Demythstifying Web Components](http://www.backalleycoder.com/2016/08/26/demythstifying-web-components/) An attempt to conclusively curb stomp the seemingly endless FUD that circulates about Web Component

## Custom Elements

* [Custom elements v1: reusable web components](https://developers.google.com/web/fundamentals/getting-started/primers/customelements) With Custom Elements, web developers can create new HTML tags, beef-up existing HTML tags, or extend the components other developers have authored.
* [The Case for Custom Elements: Part 1](https://medium.com/dev-channel/the-case-for-custom-elements-part-1-65d807b4b439) The case for why Custom Elements make sense, especially for large organizations.
* [The Case for Custom Elements: Part 2](https://medium.com/dev-channel/the-case-for-custom-elements-part-2-2efe42ce9133) A post describing some of the features that make Custom Elements compelling if you’re considering building your own component library.
* [All about HTML Custom Elements](https://github.com/shawnbot/custom-elements) A detailed overview including the differences between Custom Elements v0 and v1.
* [Custom Elements](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Custom_Elements) at Mozilla Developer Network
* [Introducing Custom Elements](https://webkit.org/blog/7027/introducing-custom-elements/) The Custom Elements API has been implemented and enabled by default in the Safari Technology Preview 18.

## Shadow DOM

* [Shadow DOM v1: self-contained web components](https://developers.google.com/web/fundamentals/getting-started/primers/shadowdom) With Shadow DOM, you can bundle CSS with markup, hide implementation details, and author self-contained components in vanilla JavaScript.
* [What's New in Shadow DOM v1 (by examples)](http://hayato.io/2016/shadowdomv1/) This document is an attempt to track the difference between Shadow DOM v0 and v1.
* [Accessibility and the Shadow DOM](http://substantial.com/blog/2014/02/05/accessibility-and-the-shadow-dom) A lesson on rendering trees, emerging technologies and tacos
* [Introducing Slot-Based Shadow DOM API](https://webkit.org/blog/4096/introducing-shadow-dom-api/) Version 1 of the Shadow DOM standard was shipped in Safari 10.0.

## HTML Templates

* [Introduction to the template elements](http://webcomponents.org/articles/introduction-to-template-element/) Templates allow teams to divide their work.

## Polyfills
* [WebComponentsjs](https://github.com/WebComponents/webcomponentsjs): A polyfill for Custom Elements, Shadow DOM, HTML Imports, Weakmap, and Mutation Observers
* [custom-elements](https://github.com/webcomponents/custom-elements): A polyfill for the v1 spec for Custom Elements.

## Libraries

* [Polymer](https://www.polymer-project.org/) Polymer is a new type of library for the web, built on top of Web Components, and designed to leverage the evolving web platform on modern browsers.
* [Skate](https://github.com/skatejs/skatejs) Skate is a web component library that is focused on being a tiny, performant, syntactic-sugar for binding behaviour to custom and existing elements without ever having to worry about when your element is inserted into the DOM.

## Best Practices

* [Web Components best practices](http://webcomponents.org/articles/web-components-best-practices/)

## Blogs

* [WebComponents.org](http://webcomponents.org/) a place to discuss and evolve web component best-practices
* [Polymer Blog](https://www.polymer-project.org/1.0/blog/) The latest goings-on with the Polymer project and in the community.

## Screencasts

* [Polycasts with Rob Dodson](https://www.youtube.com/playlist?list=PLOU2XLYxmsII5c3Mgw6fNYCzaWrsM3sMN) Rob Dodson from the Chrome Developer Relations team explores the ins and outs of Polymer.

## Who To Follow

[![Eric Bidelman](https://2.gravatar.com/avatar/e7948aac7c52b26470be80311873a398)](https://twitter.com/ebidel) | [![Addy Osmani](https://2.gravatar.com/avatar/96270e4c3e5e9806cf7245475c00b275)](https://twitter.com/addyosmani) | [![Rob Dodson](https://2.gravatar.com/avatar/95c3a3b33ea51545229c625bef42e343)](https://twitter.com/rob_dodson) | [![Web Components](https://2.gravatar.com/avatar/cedf2a3fe1ccf53aa00f50dda79cedf3)](https://twitter.com/web_components) | [![Polymer](https://avatars0.githubusercontent.com/u/2159051?v=2&s=80)](https://twitter.com/polymer)
--- | --- | --- | --- | ---
[Eric Bidelman](https://twitter.com/ebidel) | [Addy Osmani](https://twitter.com/addyosmani) | [Rob Dodson](https://twitter.com/rob_dodson) | [Web Components](https://twitter.com/web_components) | [Polymer](https://twitter.com/polymer)

[![Alex Komoroske](https://lh5.googleusercontent.com/-WlbCSDZ9t5Y/AAAAAAAAAAI/AAAAAAAAC2M/A_HM2ovbT2o/s80-c/photo.jpg)](https://twitter.com/jkomoros) | [![Pascal](https://2.gravatar.com/avatar/b32bdb1fc9fdadeb45d7a1267fdd2fc4)](https://twitter.com/PascalPrecht) | [![Zeno Rocha](https://2.gravatar.com/avatar/e190023b66e2b8aa73a842b106920c93)](https://twitter.com/zenorocha) | [![Daniel Buchner](https://2.gravatar.com/avatar/35e22073952684192bb93702a947308c)](https://twitter.com/csuwildcat) | [![Angelina Fabbro](https://2.gravatar.com/avatar/25bb0913435212f30f2fec0eb6e60dde)](https://twitter.com/hopefulcyborg)
--- | --- | --- | --- | ---
[Alex Komoroske](https://twitter.com/jkomoros) | [Pascal Precht](https://twitter.com/PascalPrecht) | [Zeno Rocha](https://twitter.com/zenorocha) | [Daniel Buchner](https://twitter.com/csuwildcat) | [Angelina Fabbro](https://twitter.com/hopefulcyborg)

[![Eduardo](https://2.gravatar.com/avatar/42327de520e674a6d1686845b30778d0)](https://twitter.com/eduardolundgren) | [![Pascal Hartig](https://avatars0.githubusercontent.com/u/9906?v=2&s=80)](https://twitter.com/passy) | [![Sindre Sorhus](https://2.gravatar.com/avatar/d36a92237c75c5337c17b60d90686bf9)](https://twitter.com/sindresorhus) | [![Christian](https://2.gravatar.com/avatar/07fcd228af02d476b1b8367d85a903b2)](https://twitter.com/codepo8)
--- | --- | --- | ---
[Eduardo lundgren](https://twitter.com/eduardolundgren) | [Pascal Hartig](https://twitter.com/passy) | [Sindre Sorhus](https://twitter.com/sindresorhus) | [Christian Heilmann](https://twitter.com/codepo8)


## License

Copyright 2014-2018, All rights reserved.

Code licensed under the:
[MIT license](http://mateusortiz.mit-license.org)

@author Mateus Ortiz <mteusortiz@gmail.com>
