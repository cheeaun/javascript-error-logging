JavaScript error logging
========================

A collection of JavaScript error logging services, and comparisons among them.

Previously, on <https://gist.github.com/cheeaun/5835757>.

Hosted services
---

- http://errorception.com/ - translate error messages to English; stack traces, source maps, smart grouping
- http://www.muscula.com/ - source maps, translate error messages to English
- [Airbrake](https://www.airbrake.io/) - tracekit, source maps. [No automatic error capture](https://github.com/airbrake/airbrake-js/issues/82).
- http://www.errorstack.com/
- [The Root Cause](https://therootcause.io/) - RootCause provides you with a comprehensive set of tools to monitor and reproduce errors in web sites / applications. Using the built-in recorder feature you’ll know exactly what the user did. By Bryntum who also makes [Siesta](https://www.bryntum.com/products/siesta/) js ui + unit testing tool
- http://jslogger.com/
- [Sentry](https://www.sentry.io/) - source maps, tracekit, breadcrumbs, [inline React error codes](https://blog.sentry.io/2016/08/10/react-minified-errors.html); [free for <150,000 events/month](https://sentry.io/pricing); open source [server](https://github.com/getsentry/sentry) and [clients](https://github.com/getsentry/raven-js)
- [Raygun](https://raygun.com/) - Error and crash reporting software, stack traces, breadcrumbs, source map support, custom data and tags, filtering, email and chat alerts, sensitive data filtering, deployment tracking, user tracking and real user monitoring (RUM), works with every major language and platform.
- https://bugsnag.com/ - source maps
- [Rollbar](https://rollbar.com/) - can [trace errors in 3rd party scripts](https://github.com/rollbar/rollbar.js/issues/108#issuecomment-121448333) as well; [free for <5000 events/month](https://rollbar.com/pricing/); source maps
- https://www.honeybadger.io/
- [{Track:js}](http://trackjs.com/) - stores timeline of events that have lead to the error
- https://www.exceptionsjs.com/
- [Usersnap](http://usersnap.com/) - stack traces; [console recorder include XHR monitoring](https://usersnap.com/features/console-recorder)
- [Atatus](https://www.atatus.com/) - real user monitoring(RUM), source maps, tracekit, timeline of events
- [Loggly](https://www.loggly.com/docs/javascript/) - [no stack tracing](https://github.com/loggly/loggly-jslogger/issues/24)
- [jsErrLog](http://jserrlog.appspot.com/) - running on the free Google AppEngine
- [Ruxit Web Monitoring](https://ruxit.com/web-monitoring/) - real user and synthetic monitoring including stacktraces, originating user action and detailed browser metrics.
- [ErrLytics](https://errlytics.com/) - errors with stacktrace, code context and event timeline which led to error. Also provides on demand analytics without any integration.

Self-hosted services
--------------------
- http://jsnlog.com/


Comparisons between services
----------------------------

* [Slant on JavaScript client-side error logging services](http://www.slant.co/topics/2615/~what-are-the-best-javascript-client-side-error-logging-services)
* [Comparison matrix in a Google Sheet](https://docs.google.com/spreadsheets/d/1IAurU073WiEr8hLeRu6rU_ilX-gaSOXfluXjUlTcQhc/edit#gid=0) by Igor Santos


Dead services
---

- https://getcoalmine.com/ [DEAD, Nov 8, 2013]
- http://damnit.jupiterit.com/ [DEAD]
- http://rescuejs.com/ [DEAD, acquired by Bugsnag]
- https://errplane.com/ [DEAD, pivoted]
- http://jserror.net/ [DEAD, probably]
- http://www.errorify.com/ - source maps [DEAD]
- https://www.proxino.com/ [DEAD]
- http://www.exceptional.io/ [DEAD, acquired by Airbrake]
- http://www.bugsense.com/ [DEAD, acquired by Splunk]
- https://crashlog.io/ [DEAD]
- http://www.geterrorzero.com/ [DEAD]
- https://www.debuggify.net/ - source maps, tracekit [DEAD]
- http://www.errzero.com/ [DEAD]
- http://qbaka.com/ [DEAD]
- http://www.exceptionhub.com/ [DEAD]

Contributing
---

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
