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

https://docs.microsoft.com/en-us/azure/architecture/patterns/
https://www.javatpoint.com/spring-3-mvc-tutorial


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
