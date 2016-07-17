# Awesome Service Workers [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated collection of service worker resources.

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
- [Related Technologies](#related-technologies)

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

## Related Technologies

- [Background Sync](https://github.com/TalAter/awesome-progressive-web-apps#background-sync)
- [Push Notifications](https://github.com/TalAter/awesome-progressive-web-apps#push-notifications)
- [App Install Banners](https://github.com/TalAter/awesome-progressive-web-apps#installable-web-apps)
