# Awesome Service Workers [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated collection of [service worker](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API) resources.

> A service worker is an event-driven worker registered against an origin and a path. It takes the form of a JavaScript file that can control the web page/site it is associated with, intercepting and modifying navigation and resource requests, and caching resources in a very granular fashion to give you complete control over how your app behaves in certain situations (the most obvious one being when the network is not available.)
>
> -- <cite>[Mozilla Developer Network - Service Worker API](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API)</cite>

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

If you want to contribute, please read the [contribution guidelines](contributing.md).

## Contents

- [Must Reads](#must-reads)
- [Learning Resources](#learning-resources)
- [Reference](#reference)
- [Browser Support](#browser-support)
- [Libraries and Tools](#libraries-and-tools)
- [Videos](#videos)
- [Case Studies](#case-studies)
- [Specific Technologies](#specific-technologies)
  - [Background Sync](#background-sync)
  - [Installable Web Apps](#installable-web-apps)
  - [Push Notifications](#push-notifications)

## Must Reads

- [Designing Offline-First Web Apps](http://alistapart.com/article/offline-first) - A fascinating look at design and UX considerations for dealing with various states of connectivity.
- [Introduction to Service Worker](http://www.html5rocks.com/en/tutorials/service-worker/introduction/) - A graceful introduction to service workers.
- [Offline Web Applications Using IndexedDB & Service Worker](https://www.udacity.com/course/offline-web-applications--ud899) - This free Udacity course is a must if you're planning to dive deep into service workers.
- [Service Workers Explained](https://github.com/slightlyoff/ServiceWorker/blob/master/explainer.md) - Service workers explained by [Alex Russell](https://github.com/slightlyoff).

## Learning Resources

- [Building Offline Sites with ServiceWorkers and UpUp](https://dev.opera.com/articles/offline-with-upup-service-workers/) - A general introduction to service workers and using UpUp to provide offline functionality in minutes.
- [Introduction to Service Worker](http://www.html5rocks.com/en/tutorials/service-worker/introduction/)
- [Service Workers 101](https://github.com/delapuente/service-workers-101) - An infographic summarizing the most important parts of service workers API.
- [ServiceWorker Cookbook by Mozilla](https://serviceworke.rs/) - A collection of recipes for different use cases.
- [The copy & paste guide to your first Service Worker](https://remysharp.com/2016/03/22/the-copy--paste-guide-to-your-first-service-worker) - Shortest available introduction, by [Remy Sharp](https://github.com/remy).
- [The offline cookbook](https://jakearchibald.com/2014/offline-cookbook/) - The bible of service worker Patterns by Jake Archibald.

## Reference

- [Background Sync Spec](https://wicg.github.io/BackgroundSync/spec/) - The WIP spec for Background Sync.
- [Service Workers - W3C Specification](https://www.w3.org/TR/service-workers/) - The official service workers spec.

## Browser Support

- [Can I Use - Service Workers](http://caniuse.com/#feat=serviceworkers) - Up-to-date browser support table of ServiceWorker API.
- [Jake Archibald - Is Service Worker ready?](https://jakearchibald.github.io/isserviceworkerready/) - Current status of ServiceWorker support in different browsers.

## Libraries and Tools

- [UpUp](http://upup.rocks/) - A popular service worker library providing complete offline functionality for your site in 1 line of code.
- [sw-toolbox](https://github.com/GoogleChrome/sw-toolbox/) - A collection of simple helpers to simplify implementing common caching patterns.
- [Manifest Generator](https://brucelawson.github.io/manifest/) - Generate a web app manifest, required for push notifications and installable web apps.

## Videos

- [Instant Loading: Building offline-first Progressive Web Apps - Google I/O 2016](https://youtu.be/cmGr0RszHc8) - A quick dive into the most common technologies and techniques for building progressive web apps.
- [Offline Web Applications Using IndexedDB & Service Worker](https://www.udacity.com/course/offline-web-applications--ud899) - This free Udacity course is a must if you're planning to dive deep into service workers.

## Case Studies

- [Service Workers in Production](https://developers.google.com/web/showcase/case-study/service-workers-iowa) - A case-study about how Google I/O 2015 web app was built.

## Specific Technologies

### Background Sync

- [Background Sync Explained](https://github.com/WICG/BackgroundSync/blob/master/explainer.md) - The official "explainer" document for background sync, including one-off synchronization and periodic synchronization.
- [Background Sync Spec](https://wicg.github.io/BackgroundSync/spec/) - The WIP spec for Background Sync.
- [Introducing Background Sync](https://developers.google.com/web/updates/2015/12/background-sync?hl=en) - A more reader friendly introduction to background sync, with some great video and code samples.

### Installable Web Apps

- [Increasing Engagement with Web App Install Banners](https://developers.google.com/web/updates/2015/03/increasing-engagement-with-app-install-banners-in-chrome-for-android?hl=en) - An intro to App Install Banners and making sure Chrome offers your web app to your users.
- [Installable Web Apps with the Web App Manifest in Chrome for Android](https://developers.google.com/web/updates/2014/11/Support-for-installable-web-apps-with-webapp-manifest-in-chrome-38-for-Android) - An introduction to installable Web Apps in Chrome for Android.

### Push Notifications

- [Can I Use - Push API](http://caniuse.com/#feat=serviceworkers) - Up-to-date browser support table of Push API.
- [Chrome Platform Status - Web Notifications](https://www.chromestatus.com/feature/5480344312610816) - Implementation status for Chrome and other browsers.
- [PWA Dev Summit 2016 codelab - Push Notifications](https://developers.google.com/web/fundamentals/getting-started/push-notifications/?hl=en) Up-to-date getting started tutorial for Progressive Web App, Push Notifications and service worker basics.
- [Using the Push API](https://developer.mozilla.org/en-US/docs/Web/API/Push_API/Using_the_Push_API) - An article introducing Push API.
