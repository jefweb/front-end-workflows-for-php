##Business in the Front:
###Front-End Workflows for PHP

Jimmy Fursman

Founder & Prinicpal, Mercutio

---

![https://www.getmercutio.com](./img/mercutio-logo.png) <!-- .element: style="border:none;box-shadow:none" -->

We're a small shop that focuses on e-Commerce.

We're based in Seattle, Washington.  

We use both PHP and Javascript.

---

##Let's Talk About

Conventions for Front-End Dev

Package Management <!-- .element: class="fragment" data-fragment-index="1" -->

CSS Pre-Processing <!-- .element: class="fragment" data-fragment-index="2" -->

Task Automation <!-- .element: class="fragment" data-fragment-index="3" -->

Drawbacks & Limitations  <!-- .element: class="fragment" data-fragment-index="4" -->

---

##Why a Front-End Workflow?

A convention that was flexible & reuseable <!-- .element: class="fragment" data-fragment-index="0" -->

We’re a small shop, we wear multiple hats <!-- .element: class="fragment" data-fragment-index="1" -->

Ultimately speed up our Dev & QA cycles <!-- .element: class="fragment" data-fragment-index="2" -->

We like Laravel's Elixer, but need a global solution <!-- .element: class="fragment" data-fragment-index="3" -->

---

##How PHP-Specific is this?

Really just our context

A few of the toolset choices <!-- .element: class="fragment" data-fragment-index="0" -->

Code organization <!-- .element: class="fragment" data-fragment-index="1" -->

Infrastructure, build, and deployment process   <!-- .element: class="fragment" data-fragment-index="2" -->

---

#So Many Tools! 

---

![npm](./img/npm.png) <!-- .element: width="300" style="border:none;box-shadow:none" -->

##Start with NPM

It's a lot like composer

---

npm 'dependencies' == composer 'require'

---

npm 'devDepencies' == composer 'require-dev'

---

##Bower or Browserify 

For libraries like jQuery or Bootstrap

---

![Bower](./img/bower.png) <!-- .element: width="300" style="border:none;box-shadow:none" -->

Bower was basically redundant to npm 

And was bad at dependency management   <!-- .element: class="fragment" data-fragment-index="1" -->

---

![Browserify](./img/browserify.png) <!-- .element: width="600" style="border:none;box-shadow:none" -->

##So we use Browserify 

It allows you to bundle <!-- .element: class="fragment" data-fragment-index="0" -->

Has a package format like npm <!-- .element: class="fragment" data-fragment-index="1" -->

Also works with standalone JS files   <!-- .element: class="fragment" data-fragment-index="2" -->

---

![LESS](./img/less.png) <!-- .element: width="300" style="border:none;box-shadow:none" -->

##LESS for CSS Processing

Modular, reusable snippets <!-- .element: class="fragment" data-fragment-index="0" -->

Variables and calculations <!-- .element: class="fragment" data-fragment-index="1" -->

Code structure to match HTML <!-- .element: class="fragment" data-fragment-index="2" -->

No added dependencies <!-- .element: class="fragment" data-fragment-index="3" -->

---

![GRUNT](./img/grunt.png) <!-- .element: width="150" style="border:none;box-shadow:none" -->

##Grunt is the Glue

It's really just a task runner

---

##Grunt is also Easy

Create individual actions in pure JSON <!-- .element: class="fragment" data-fragment-index="0" -->

Assemble actions into a task queue <!-- .element: class="fragment" data-fragment-index="1" -->

Trigger task via command or event <!-- .element: class="fragment" data-fragment-index="2" -->

---

##Grunt Plugins

File watchers know when CSS/JS is saved <!-- .element: class="fragment" data-fragment-index="0" -->

Check syntax, enforce code style <!-- .element: class="fragment" data-fragment-index="1" -->

Aggregate and minify your CSS/JS <!-- .element: class="fragment" data-fragment-index="2" -->

Refresh your browser window on success(!) <!-- .element: class="fragment" data-fragment-index="3" -->

---

##Deployments?

1. 'git clone' <!-- .element: class="fragment" data-fragment-index="0" -->

2. 'composer install' <!-- .element: class="fragment" data-fragment-index="1" -->

3. 'npm install' <!-- .element: class="fragment" data-fragment-index="2" -->

4. 'grunt deploy' <!-- .element: class="fragment" data-fragment-index="3" -->

5. beer. <!-- .element: class="fragment" data-fragment-index="4" -->

---

##Drawbacks

* NPM breaks the internet

* CSS often needs refactoring

* All machines need NodeJS

---

##Resources

* [Installing Node](https://coolestguidesontheplanet.com/installing-node-js-on-osx-10-10-yosemite/)
* [Intro Browserify](http://word.bitly.com/post/101360133837/browserify)
* [Less for CSS](http://verekia.com/less-css/dont-read-less-css-tutorial-highly-addictive/)
* [Grunt Basics](http://www.hongkiat.com/blog/automate-workflow-with-grunt/)

---

![https://www.getmercutio.com](./img/mercutio-logo.png) <!-- .element: style="border:none;box-shadow:none" -->

##Thanks!

jimmy@getmercutio.com

@jefweb

https://github.com/jefweb/front-end-workflows-for-php



