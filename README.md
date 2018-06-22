[![Backers on Open Collective](https://opencollective.com/react-pwa/backers/badge.svg)](#backers) [![Sponsors on Open Collective](https://opencollective.com/react-pwa/sponsors/badge.svg)](#sponsors) [![Dependencies Status](https://david-dm.org/Atyantik/react-pwa.svg)](https://david-dm.org/Atyantik/react-pwa)
[![devDependencies Status](https://david-dm.org/Atyantik/pawjs/dev-status.svg)](https://david-dm.org/Atyantik/pawjs?type=dev)
[![Build Status](https://travis-ci.org/Atyantik/pawjs.svg?branch=master)](https://travis-ci.org/Atyantik/pawjs)
[![Known Vulnerabilities](https://snyk.io/test/github/Atyantik/pawjs/badge.svg)](https://snyk.io/test/github/Atyantik/pawjs)
[![Greenkeeper badge](https://badges.greenkeeper.io/Atyantik/pawjs.svg)](https://greenkeeper.io/)  

[![Join the chat at https://gitter.im/react-pwa](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/react-pwa/Lobby?utm_source=share-link&utm_medium=link&utm_campaign=share-link)


<div style="text-align:center"><img src="https://www.atyantik.com/wp-content/uploads/2018/06/72-72.png" /></div>

# Paw JS - The plugable framework
A highly scalable & plugable, **Progressive Web Application *Framework*** with the best Developer Experience.
This framework utilizes the power of React with Webpack and is build on top of webpack/tapable for unlimited extendability.


[https://www.reactpwa.com is built with this awesome framework. Why don't you check it out.](https://www.reactpwa.com/)  


#### Current Repo in Action
To view how the current repository is running please visit [https://demo.reactpwa.com](https://demo.reactpwa.com)

#### No configuration required
You start the development with nothing but just one single file i.e. `src/routes.js`

#### Features
##### PWA - Progressive Web Applications
Create Progressive web application with ReactJS. As we all know, Progressive Apps are not supported everywhere, but we have added support for Safari & Chrome so your application can work as 
standalone applications when added to home-screen or saved as desktop app.

##### Code splitting
The very difficulty faced when developing enterprise application is code splitting. We don't need everything in a single JS file. Why not simply split the code with `import()` and create bundles!
We make it really easy here to just create a page that returns an array of routes. Code is split and loaded automatically when the respective route is called.

##### ES6/7 Compatible
Using babel, we support next generation JavaScript syntax including Object/Array destructuring, arrow functions, JSX syntax and more...  

##### Universal Routing with React-Router
We are using the most accepted React router for routing the application. Add your favorite /about, /contact, /dashboard pages.

##### Offline support with Google Workbox
Yes your application is offline available. Run without internet. Pretty cool huh?? Well all thanks to service workers and google workbox
for handling the cache & network strategies.  

##### SSR - Server side rendering
The best way to get your application SEO-ed is enable Server side rendering i.e. Universal applications
You can have SSR running during development as well.    

##### SEO
Our customized routes enable creating meta tags to create Twitter, Google+, Linkedin, Facebook cards. We know how important SEO is to an application.  

##### HSTS Supported
Enable HSTS for secure sites. Options to define maxAge and preload of HSTS. All with very simple configuration.  


### License
This project is licensed under the MIT license, Copyright (c) 2018 Atyantik Technologies Private Limited. For more information see [LICENSE.md]("https://github.com/Atyantik/pawjs/blob/master/LICENSE.md").  