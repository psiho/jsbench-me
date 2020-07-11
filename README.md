![](https://github.com/psiho/jsbench-me/blob/master/images/jsbenchme-logo-100.png)

--------
## V1 is out (2020-07-12)! Complete rewrite done. Find more about it in the [ChangeLog](https://github.com/psiho/jsbench-me/wiki/Change-log). Bug reports and feature requests needed!
--------

# jsbench.me - JavaScript performance benchmarking playground

This is a public [Wiki](https://github.com/psiho/jsbench-me/wiki) & [issue tracker](https://github.com/psiho/jsbench-me/issues) for [jsbench.me](https://jsbench.me) project.

Jsbench.me is performance benchmarking playground for JavaScript, heavily inspired and influenced by jsperf.com and jsfiddle.net. It uses Benchmarkjs.com to execute test suites.

Now you can execute and compare  execution speed of different JavaScript code snippets, but also share it and collaborate with others online through simple and short URL.

![screenshot](https://github.com/psiho/jsbench-me/blob/master/images/screenshot-0.2.png)

**Features:**

* Free to use
* Create multiple tests in Suitecase.
* sort & resize test
* run individual tests
* "Setup JavaScript" and "teardown JavaScript" to execute before and after each test run.
* "Setup HTML" to test DOM manipulation.
* Include external libraries through simple `<SCRIPT>` tag in "Setup HTML"
* Test run in sanboxed Iframe to increase security
* Test suite versioning
* Fork test sutes
* List user's public test suites
* Fast and efficient UI built as single page app (Reactjs/Mobx)
* Reliable and scalable infrastructure, mostly Amazon AWS (Cognito user pool, API Gateway, Lambda, DynamoDB)

**Important:**
jsbench.me is currently tested only on latest browsers. I'm working on polishing and testing on different browsers. Your comments and issue reports are very welcomed in this stage!
