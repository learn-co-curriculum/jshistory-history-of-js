# History of JavaScript

## Introduction

In many interview questions, it becomes very useful to be able to discuss the shifts
and trends in the history of the language. It suggests to your interviewer or someone
you're working with that you understand how the language evolved to meet the challenges
that the ever-growing web presented the language. Here's a basic outline.

## Learning Goals

1. Describe the JavaScript language and its uses
2. Outline the history of JavaScript

## Describe the JavaScript Language and its Uses

_JavaScript_, commonly abbreviated as _JS_, is the programming language of the web.
Along with HTML and CSS, it's used to create virtually all the web pages and
apps you interact with, from Google to Facebook to Wikipedia to Amazon to
Netflix.

A language of many talents, JavaScript allows us to create incredibly diverse
applications that run in the browser, on the back-end as NodeJS, on the desktop, and on
mobile devices. It's a flexible language, allowing us to program in many
different styles — [functional][fn] and [object-oriented][oo], in particular — mixing and
matching concepts to adapt to our needs. It's powerful, scalable, and has a
robust community of developers churning out new code and advancing the language.

Additionally, it has an expansive collection of libraries that we can leverage
to work faster / better called [npm][].

## Outline the History of JavaScript

The first version of JavaScript was built incredibly quickly in 1995. There were
a few other competitors vying to become the language of the web, but they never
gained enough traction to knock off JavaScript. And then... not much happened.
There were incremental improvements and adjustments, but JavaScript development
around 2000 very much resembled JavaScript development in the mid-1990s.

### The Emergence of Asynchronous JavaScript

Around the turn of the century, Microsoft wanted to give its customers a way to
access their email via a web browser, so they added a new JavaScript feature to
Internet Explorer that allowed an already-loaded web page to fire off a request
for additional data. It was a huge improvement over existing webmail services
that required the whole page to be reloaded in order to check for new email. The
process of making requests for additional data became known as _Asynchronous
JavaScript and XML_, or _AJAX_. (We'll take a long look at AJAX and asynchronous
code execution later on in the JavaScript material.) By 2004, when Gmail came
along with a heavy dependence on AJAX, JavaScript was in the early stages of a
rise in popularity and usefulness that has continued to the present day.

### Standardization and Modernization

Even though AJAX provided a lot of useful functionality to the language,
JavaScript was still difficult to program. Different browsers implemented
different features in different ways. There were a few competing camps which all
had different ideas about what the language should be. In early 2009, everyone
came together to agree on standardization. The fifth version of JavaScript was
released in late 2009. It's known as _ES5_ ('ES' for _ECMAScript_, the official
name of the JavaScript specification) or _Harmony_ (because it harmonized
competing implementations of the ECMAScript specification). (Note: We still
refer to the language as JavaScript, and use the particular version titles only
when we need to point to particular version features.)

Harmonization was great, but the language was still lacking modern language
features common to most standard programming languages like PHP, Java, C, Python
and Ruby. JavaScript began to address those concerns in 2015 with the unveiling
of _ES6_ or _ES2015_, the sixth version of JavaScript. Since then, they have
released updates every year, including _ES2016_ and _ES2017_, both of which have
brought additional modern features into the language. 

## Compilation and JavaScript

The name _JavaScript_ was chosen as a marketing ploy: the _Java_ language was
all the rage in 1995. The two languages share very little in common. Some JS
syntax is borrowed from Java (to make it more familiar for those early
developers coming over from the world of Java), but that's about it.

Unlike Java, JavaScript code doesn't need to be compiled. The code that you
write in a JavaScript file is the exact same code that the web browser parses
and runs. In a compiled language like Java, you write some code in a human-
readable format, and then the compiler takes that code and essentially
translates it into machine-readable code. That means that it's very difficult to
open up the source code for an application written in a compiled language and
poke around in it to understand what's going on.

Because JavaScript doesn't get compiled, that is exactly what we can do with
JavaScript code. Towards the end of this JavaScript curriculum, you'll find
yourself able to go to a website you like, open up the source code using your
browser's developer tools, and look directly at all of the JavaScript code used
on that site. This is a powerful feature of the language and an incredible tool
for learning by example.

A popular witticism is that: "Java is to JavaScript as ham is to hamster."

## Post ES6 &amp Rise of the Frameworks

With ES6's rollout, many tools were introduced to ensure that ES6 code could also
work in older browsers. This lead developers to add "transpilation" – converting
ES6 code to less-new work-arounds. As a side-effect of this "pipeline," developers
stopped thinking about JavaScript as a "scripting" language and started thinking
about building frameworks for complex, robust applications. Entrants of this era
were Angluar, Ember, Angular 2. React also made its appearance in this era. We're
now (arguably) in the second generation of frameworks anchored by React as the 
incumbent with Vue.js and others pushing innovation. Ultimately, however, these
frameworks are all written *in* JavaScript: they're merely optimizations, conventions,
and best practices that collect under a single framework name.

## Conclusion

You're all caught up! The future of JavaScript is _yours_ to write.

[npm]: https://www.npmjs.com/
