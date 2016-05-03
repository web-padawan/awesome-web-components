# Web Components the Right Way

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> This is a guide intended to introduce to Web Components. Everyone can contribute here!

- [Web Components the Right Way]()
  - [Specs](#specifications)
  - [Blogs](#blogs)
  - [Getting Started](#getting-started)
  - [Reading](#reading)
  - [Interop](#interoperability)
  - [Generators](#generators)
  - [Tests](#tests)
  - [Discover](#discover)
  - [Best Practices](#best-practices)
  - [Style Guides](#style-guides)
  - [Perfomance](#performance)
  - [Libraries](#libraries)
  - [Screencasts](#screencasts)
  - [Suport](#support)
  - [Concatenating](#concatenate)
  - [Boilerplates](#boilerplates)
  - [Who to follow](#who-to-follow)
  - [License](#license)


> Web Components the Right Way was made with love by [Mateus Ortiz](https://twitter.com/mteusortiz)

## Specifications

* [Web Components](http://w3c.github.io/webcomponents/explainer/) - This document is a non-normative reference, which provides an overview of Web Components.
* [Shadow Dom](http://w3c.github.io/webcomponents/spec/shadow/) - Spec of Shadow Dom
* [HTML Imports](http://w3c.github.io/webcomponents/spec/imports/) - Spec of html imports
* [Template](https://html.spec.whatwg.org/multipage/scripting.html#the-template-element) Spec of Template
* [Custom Elements](http://w3c.github.io/webcomponents/spec/custom/) - Spec Custom Elements is cherry on cake.


## Blogs

* [WebComponents.org](http://webcomponents.org/) a place to discuss and evolve web component best-practices
* [Polymer Articles](https://www.polymer-project.org/articles/) Articles core concepts of build apps on top of Polymer and web components
* [Polymer Blog](https://blog.polymer-project.org/) Blog with news of polymer.



## Reading

* [Introduction to the template elements](http://webcomponents.org/articles/introduction-to-template-element/) Templates allow teams to divide their work.
* [Polymer vs. X-Tag](http://pascalprecht.github.io/2014/07/21/polymer-vs-x-tag-here-is-the-difference/) Polymer vs. X-Tag - Here's the difference
* [Ten Principles for Great General Purpose Web Components](https://github.com/basic-web-components/components-dev/wiki/Ten-Principles-for-Great-General-Purpose-Web-Components) This page lays out a set of principles for creating general-purpose web components that can be readily adopted in a wide range of sites and application.
* [Introduction To Custom Elements](http://www.smashingmagazine.com/2014/03/introduction-to-custom-elements/) A Detailed Introduction To Custom Elements
* [Accessibility and the Shadow DOM](http://substantial.com/blog/2014/02/05/accessibility-and-the-shadow-dom) A lesson on rendering trees, emerging technologies and tacos
* [Modular future Web Components](https://css-tricks.com/modular-future-web-components/) A Guide to Web Components
* [Polymer vs Angular](http://www.binpress.com/blog/2014/06/26/polymer-vs-angular/) Here’s the difference between Polymer and Angular
* [Building single page apps using web components](https://www.polymer-project.org/articles/spa.html) The Polymer approach to building single page applications
* [Web Components é uma Revolução? PT-br](http://www.akitaonrails.com/2014/07/06/web-components-e-uma-revolucao) Existe uma nova celebridade na cidade, e seu nome é "Web Components". Ultimamente muitos apresentam esta nova tecnologia como o 'Santo Graal' que vai resolver todos os problemas da Web. Este artigo não é um apoio incondicional, não é uma crítica negativa irrefutável, mas meramente uma apresentação de perspectivas com o objetivo de dar clareza.
* [The State of the Componentised Web](http://www.leggetter.co.uk/2014/08/06/state-componentised-web.html) The idea of building applications out of a number of independent components isn’t anything new. But with Web Components is a good time to look at component-based application development, how we benefit from taking this approach, how we can build our applications in this way using existing technologies and how we’re likely to be building our front-end web apps in the future.
* [Integrating Web Components with AngularJS](pascalprecht.github.io/2014/10/25/integrating-web-components-with-angularjs/) This article focuses on the integration of Web Components with the AngularJS of today and the AngularJS of tomorrow.
* [Introducing Polymer 0.5.1](https://blog.polymer-project.org/releases/2014/11/12/release-0.5.1/) We announce significant releases here on the blog, highlighting the major new features as well as breaking changes.
* [Polymer Web Components With Marionette.js](http://blog.jeremyfairbank.com/javascript/polymer-web-components-with-marionette-js/) JavaScript is a playground. If you disagree, then I encourage you to read Atwood’s Law. A quick Google search will reveal the law in full force with assemblers, machine emulators, and programming languages all written in JavaScript. That is just a small sampling. Go peruse the npm registry for plenty of build tools, frameworks, and servers written in JavaScript. We are tinkerers, especially in the JavaScript community. Sometimes our creations are practical and sometimes they are just fun.
* [Creating a Polymer Chat App with Material Design](https://www.pubnub.com/blog/2015-01-15-creating-a-polymer-chat-app-with-material-design/) I am showing how to create yet another chat app with Material Design using Polymer to create a simple but visually appealing app with a great user-experience
* [Best Practice for Creating Custom Elements](https://www.broken-links.com/2015/01/27/best-practice-creating-custom-elements/) It looks like custom elements, and web components in general, are beginning to break through into general developer consciousness, as I see more and more articles and talks discussing what they are, what they are good for, and how to make them.
* [Web Components and their role in the future of web development](http://kaytcat.github.io/web-components/) A discussion surrounding the history and future of Web Components in modern web development.
* [Understanding Web Components](https://medium.com/the-ui-files/understanding-web-components-d051baa66019) Another overview of web components specs and explanation of their advantages: composability, encapsulation, reusability.

## Getting Started

* [Using Polymer to Create Web Components](http://code.tutsplus.com/tutorials/using-polymer-to-create-web-components--cms-20475) To bridge the gap and give developers access to this rich functionality now, Google has created the Polymer library which serves as a set of polyfills to bring the promise of Web Components to you today.
* [Custom Elements](http://www.html5rocks.com/en/tutorials/webcomponents/customelements/) defining new elements in HTML
* [Exploring HTML Imports](http://robdodson.me/exploring-html-imports/) Web Components have come a long way in the past few months. HTML Imports allow you to load additional documents into your page without having to write a bunch of ajax. This is great for Custom Elements where you might want to import a suite of new tags.
* [A No-Nonsense Guide to Web Components](http://cbateman.com/blog/a-no-nonsense-guide-to-web-components-part-1-the-specs/) A multi-part series with a crash course on Web Components specs, polyfills, performance, accessibility, and more.


## Interoperability

* [React and Custom Elements](http://addyosmani.com/blog/component-interop-with-react-and-custom-elements/) Component Interop with React and Custom Elements
* [Interop Sass](https://github.com/webcomponents/sass-interop) A demo of interoperability between Sass and Polymer.
* [Interop Less](https://github.com/webcomponents/less-interop) A demo of interoperability between Less and Polymer.
* [Interop Angular](https://github.com/webcomponents/angular-interop) A demo of interoperability between Polymer and AngularJs.
* [Custom Element Interoperability](https://www.polymer-project.org/articles/polymer-xtag-vanilla.html) Using Polymer, X-Tag, and Vanilla Custom Elements


## Generators

* [Generator Elements](https://github.com/webcomponents/generator-element) A Yeoman Generator that provides a functional boilerplate to easily create Custom Elements using Polymer, X-Tag or VanillaJS.
* [Generator Polymer](https://github.com/yeoman/generator-polymer/) Yeoman generator for scaffolding Polymer apps
* [Geneator X-Tag](https://github.com/x-tag/yo-x-tag-generator) X-Tag generator for Yeoman
* [Generator Bosonic](https://github.com/bosonic-labs/yeoman-bosonic) Yeoman Generator Bosonic
* [Slush Element](https://github.com/webcomponents/slush-element) A Slush Generator that provides a functional boilerplate to easily create Custom Elements using Polymer, X-Tag or VanillaJS.


## Tests

* [Seed-Element](https://github.com/PolymerElements/seed-element) Polymer element boilerplate Tests
* [Web Component Tester](https://github.com/Polymer/web-component-tester) web-component-tester makes testing your web components a breeze!


## Discover

* [Bower search](http://bower.io/search/?q=web-components) Bower search Web Components
* [Built Polymer](http://builtwithpolymer.org/) Built with Polymer
* [Components Kitchen](https://component.kitchen/) The best ingredients for your web apps
* [Custom Elements](https://customelements.io/) a web components gallery for modern web apps
* [Polymer Tools Designer](https://www.polymer-project.org/tools/designer/) Designer is a drag and drop tool for prototyping apps using Polymer. Save your experiments as Github gists.


## Best Practices

* [Web Components best practices](http://webcomponents.org/articles/web-components-best-practices/) Web Components (WC) are a new set of web platform features that enable developers to build applications in a declarative, composable way.
* [How should I name my element?](http://webcomponents.org/articles/how-should-i-name-my-element/) Naming is always a challenging task when developing a component. We can create truly complex pieces of code but we still have a hard time to name a simple variable.
* [WEB COMPONENTS AND YOU – DANGERS TO AVOID](https://www.christianheilmann.com/2014/04/18/web-components-and-you-dangers-to-avoid/) Web Components are a hot topic now. Creating widgets on the web that are part of the browser’s rendering flow is amazing.
* [Melhores Práticas Web Components PT-br](http://tableless.com.br/melhores-praticas-web-components/) Conheça práticas simples que podem ajudar na organização do seu web component.
* [The Web’s Declarative, Composable Future](http://addyosmani.com/blog/the-webs-declarative-composable-future/) This year, the platform is getting Web Components, bringing forward a way to make the relationships between markup and behaviour a lot less vague when you’re looking at the HTML.


## Style Guides

* [Google Web Components Style Guide](https://github.com/GoogleWebComponents/style-guide) This guide serves as an extension to the Google JavaScript Style Guide with additional style guidance around authoring Web Components, particuarly those in this element collection. It is targeted at Google engineers, but may be useful for others too.


## Performance

* [High Performance Web Components](https://www.youtube.com/watch?v=m3EPIeKaDCU) HTML5DevConf May 2014: Steve Souders, Fastly : High Performance Web Components


## Libraries

* [Polymer](https://www.polymer-project.org/) Polymer is a new type of library for the web, built on top of Web Components, and designed to leverage the evolving web platform on modern browsers.
* [X-Tag](https://x-tag.readme.io/) X-Tag is a small JavaScript library, created and supported by Mozilla, that brings Web Components Custom Element capabilities to all modern browsers.
* [Bosonic](http://bosonic.github.io/) Bosonic is a set of tools that enable you to build Web Components as the spec currently describes, and supporting not-so-modern browsers like IE9.
* [Polymer Dart](https://www.dartlang.org/polymer/) Polymer.dart is a Dart port of Polymer. Build Web Components with Dart, and interoperate with Web Components built with JavaScript.
* [Skate](https://github.com/skatejs/skatejs) Skate is a web component library that is focused on being a tiny, performant, syntactic-sugar for binding behaviour to custom and existing elements without ever having to worry about when your element is inserted into the DOM.


## Screencasts

* [Setting up Bower and Polymer](https://www.youtube.com/watch?v=WX6Hbi-xSUI) I wanted to show how easy it is to get Bower and Polymer setup.
* [YOLOmer! Polymer and Yeoman for lighting fast dev](https://www.youtube.com/watch?v=INH_OW4lFSs) 'Allo! Rob Dodson here, your host on this tour of the new Polymer generator for Yeoman.
* [Introducing the Polymer Designer tool](https://www.youtube.com/watch?v=djQh8XKRzRg) We're really excited to show off our new Designer tool, which makes building prototypes with Polymer super easy. In this video I'll walk you through the basics of creating a simple maps app, and along the way we'll touch on some of the interesting features that Designer brings to the table.
* [Ferramenta Polymer Designer PT-br](https://www.youtube.com/watch?v=yKR3VO0NF3Y&list=UU5f2WvUyrAkoktfiIuu7a-A) Introdução sobre Polymer Tools Designer ferramenta de prototype de web components.
* [Configurando Bower e Polymer PT-br](https://www.youtube.com/watch?v=owT5n9jlzVI&list=UU5f2WvUyrAkoktfiIuu7a-A) mostrando como é fácil começar a instalação do Bower e do Polymer


## Support

* [Are We Componentized Yet?](http://jonrimmer.github.io/are-we-componentized-yet/) Tracking the progress of Web Components through standardisation, polyfillification, and implementation.


## Concatenate

* [Vulcanize](https://github.com/polymer/vulcanize) Concatenate a set of Web Components into one file


## Boilerplates

* [Polymer Boilerplate](https://github.com/webcomponents/polymer-boilerplate) A bare minimum custom element starter-kit using Polymer.
* [X-Tag Boilerplate](https://github.com/webcomponents/xtag-boilerplate) A bare minimum custom element starter-kit using X-Tag.
* [VanillaJS Boilerplate](https://github.com/webcomponents/element-boilerplate) A bare minimum custom element starter-kit using VanillaJS.


## Who To Follow

[![Eric Bidelman](https://2.gravatar.com/avatar/e7948aac7c52b26470be80311873a398)](https://twitter.com/ebidel) | [![Addy Osmani](https://2.gravatar.com/avatar/96270e4c3e5e9806cf7245475c00b275)](https://twitter.com/addyosmani) | [![Rob Dodson](https://2.gravatar.com/avatar/95c3a3b33ea51545229c625bef42e343)](https://twitter.com/rob_dodson) | [![Web Components](https://2.gravatar.com/avatar/cedf2a3fe1ccf53aa00f50dda79cedf3)](https://twitter.com/web_components) | [![Polymer](https://avatars0.githubusercontent.com/u/2159051?v=2&s=80)](https://twitter.com/polymer)
--- | --- | --- | --- | ---
[Eric Bidelman](https://twitter.com/ebidel) | [Addy Osmani](https://twitter.com/addyosmani) | [Rob Dodson](https://twitter.com/rob_dodson) | [Web Components](https://twitter.com/web_components) | [Polymer](https://twitter.com/polymer)

[![Alex Komoroske](https://lh5.googleusercontent.com/-WlbCSDZ9t5Y/AAAAAAAAAAI/AAAAAAAAC2M/A_HM2ovbT2o/s80-c/photo.jpg)](https://twitter.com/jkomoros) | [![Pascal](https://2.gravatar.com/avatar/b32bdb1fc9fdadeb45d7a1267fdd2fc4)](https://twitter.com/PascalPrecht) | [![Zeno Rocha](https://2.gravatar.com/avatar/e190023b66e2b8aa73a842b106920c93)](https://twitter.com/zenorocha) | [![Daniel Buchner](https://2.gravatar.com/avatar/35e22073952684192bb93702a947308c)](https://twitter.com/csuwildcat) | [![Angelina Fabbro](https://2.gravatar.com/avatar/25bb0913435212f30f2fec0eb6e60dde)](https://twitter.com/hopefulcyborg)
--- | --- | --- | --- | ---
[Alex Komoroske](https://twitter.com/jkomoros) | [Pascal Precht](https://twitter.com/PascalPrecht) | [Zeno Rocha](https://twitter.com/zenorocha) | [Daniel Buchner](https://twitter.com/csuwildcat) | [Angelina Fabbro](https://twitter.com/hopefulcyborg)

[![Eduardo](https://2.gravatar.com/avatar/42327de520e674a6d1686845b30778d0)](https://twitter.com/eduardolundgren) | [![Pascal Hartig](https://avatars0.githubusercontent.com/u/9906?v=2&s=80)](https://twitter.com/passy) | [![Sindre Sorhus](https://2.gravatar.com/avatar/d36a92237c75c5337c17b60d90686bf9)](https://twitter.com/sindresorhus) | [![Christian](https://2.gravatar.com/avatar/07fcd228af02d476b1b8367d85a903b2)](https://twitter.com/codepo8)
--- | --- | --- | --- | ---
[Eduardo lundgren](https://twitter.com/eduardolundgren) | [Pascal Hartig](https://twitter.com/passy) | [Sindre Sorhus](https://twitter.com/sindresorhus) | [Christian Heilmann](https://twitter.com/codepo8)


## License

Copyright 2014, All rights reserved.

Code licensed under the:
[MIT license](http://mateusortiz.mit-license.org)

@author Mateus Ortiz <mteusortiz@gmail.com>
