# Document
Contains important documents for reference

## Important Links
- [Pivotal-Cloud-Foundry-Knowledge-Base](https://discuss.pivotal.io/hc/en-us/categories/200072648-Pivotal-Cloud-Foundry-Knowledge-Base)
- [Spring dependency management](https://gist.github.com/tygern/7ae839d0165e7f2bd141402654dc8966)
- [spring-cloud-services](https://docs.pivotal.io/spring-cloud-services/common/client-dependencies.html)
- [platform-acceleration-lab](https://platform-acceleration-lab-links-v1.cfapps.io/)
- [cloud.rohitkelapure.com](http://cloud.rohitkelapure.com/2016/10/snap-analysis-of-applications.html)
- [debugging-the-buildpack](https://github.com/cloudfoundry/java-buildpack/blob/master/docs/debugging-the-buildpack.md)
- [ephemerol](https://github.com/Pivotal-Field-Engineering/ephemerol)
- [Practical Microservices](https://docs.google.com/document/d/1WU7pKwW-Sx5Wrc0pQoM7r4vrSanXa2VcrQ1F6siCwvY/edit#heading=h.xvv6bc2hme7d)
- [microservices.io](http://microservices.io/index.html)
- [Value-Objects](https://www.infoq.com/presentations/Value-Objects-Dan-Bergh-Johnsson)
- [event-driven-data-management-microservices](https://www.nginx.com/blog/event-driven-data-management-microservices/)
- [cognizant-pal-v1.cfapps.io](https://cognizant-pal-v1.cfapps.io)
- [microservices-monoliths-noops](http://blog.arungupta.me/microservices-monoliths-noops/)
- [design-patterns-for-microservices](https://azure.microsoft.com/en-in/blog/design-patterns-for-microservices/)
- [Patterns](https://docs.microsoft.com/en-us/azure/architecture/patterns/)
- [Spring MVC](https://www.javatpoint.com/spring-3-mvc-tutorial)
- [Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation](http://www.synchronit.com/downloads/Continuous%20Delivery%20-%20Reliable%20Software%20Releases%20Through%20Build,%20Test%20And%20Deployment%20Automation.pdf)
- [Migrating to Cloud Native Application Architectures](https://download3.vmware.com/vmworld/2015/downloads/oreilly-cloud-native-archx.pdf)
- [Java Re-Defined](http://www.java-redefined.com/2013/08/java-collections-internal-working.html)
- [Journal Dev](http://www.journaldev.com/2888/spring-tutorial-spring-core-tutorial)
- [How todo In Java](http://howtodoinjava.com/)
- [httpstatuscodes](http://www.restapitutorial.com/httpstatuscodes.html)
- [spring_annotations_cheat_sheet](http://files.zeroturnaround.com/pdf/zt_spring_annotations_cheat_sheet.pdf)

```
http://howtodoinjava.com/java-tutorials-list-howtodoinjava 
https://blog.udemy.com/java-interview-questions
http://www.journaldev.com/2366/core-java-interview-questions-and-answers
https://www.javacodegeeks.com/wp-content/uploads/2017/01/Spring-Framework-Cookbook.pdf
http://www.java2novice.com
https://dzone.com/articles/developing-jsf-applications-with-spring-boot
https://dzone.com/articles/when-use-mongodb-rather-mysql
https://dzone.com/articles/spring-projects-best-practices-episode-i
https://dzone.com/articles/making-the-case-for-and-against-lift-and-shift-clo
https://www.upwork.com/hiring/data/sql-vs-nosql-databases-whats-the-difference/
https://dzone.com/articles/sql-vs-nosql
http://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/
https://www.upwork.com/hiring/data/sql-vs-nosql-databases-whats-the-difference/
https://howtodoinjava.com/spring/spring-restful/spring-restful-client-resttemplate-example/
http://www.baeldung.com/spring-annotation-bean-pre-processor
http://www.baeldung.com/spring-boot-custom-starter
http://www.bmc.com/blogs/microservices-vs-soa-whats-difference/
```



## Debug in PCF
This is the three steps which we need to follow to debug a PCF application:
```
1) cf set-env spring-music JBP_CONFIG_DEBUG '{enabled:true}'
2) Create an SSH tunnel: cf ssh -N -T -L <localport>:localhost:<remote port> spring-music
3) Go to Intellij and setup a remote debug profile. Give the localhost post in the dialog box.
```
```
Anwar's email id - achirakkattil@pivotal.io
```
