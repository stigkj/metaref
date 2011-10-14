Introduction
============

I am always on the lookout for new technologies, frameworks and other fun stuff, but have always
lacked a place to try these out. So this is really a play ground for all the stuff I find interesting
and want to try out more than just reading about the stuff.

I guess the problem has not been that I had nowhere to try this new fun stuff, but more that I
newer kicked myself in the but and just tried it out :-)

Initial TODOs
-------------
* Move these TODOs to GitHub's Issues
    * Use nice colours and names for labels/milestones; there is a blog or something describing this, but cannot find it
* Use liquibase with a web-view with changes that must be applied
* Use the monitoring framework (gh/codahale/metrics) with scala version too
* Encrypt passwords with Jasypt which gives a web-view for entering the master password for decrypting
    * Integrate this with Spring Security
* Maybe use play 2, coding in scala or grails
* Use Vagrant for setting up environment locally
    * Also use it for integration testing
    * Maybe call Vagrant from gradle through JRuby
* Look at Spring reference web-app
* Spring Data for JPA access
* Be an OSGI app, run under Spring DM server, maybe Spring Dynamic Modules
* Have 2 web-apps talking to each other through Spring Integration
* Add a batch that uses Spring Batch
* Run under Spring tc server in development to use Spring Insight
* Add Jolokia for doing JMX-over-REST
* Try out Graphite graphing web-app
    * Use Etsy's statsd Node.js server for collecting
    * Call statsd from code, maybe create module for codahale's metric library that does this