# Document
Contains important documents for reference

## Important Links
```
01.https://discuss.pivotal.io/hc/en-us/categories/200072648-Pivotal-Cloud-Foundry-Knowledge-Base
02.https://gist.github.com/tygern/7ae839d0165e7f2bd141402654dc8966
03.https://docs.pivotal.io/spring-cloud-services/common/client-dependencies.html
04.https://platform-acceleration-lab-links-v1.cfapps.io/
05.http://cloud.rohitkelapure.com/2016/10/snap-analysis-of-applications.html
06.https://github.com/cloudfoundry/java-buildpack/blob/master/docs/debugging-the-buildpack.md
07.https://github.com/Pivotal-Field-Engineering/ephemerol
08.https://docs.google.com/document/d/1WU7pKwW-Sx5Wrc0pQoM7r4vrSanXa2VcrQ1F6siCwvY/edit#heading=h.xvv6bc2hme7d
09.http://microservices.io/index.html
10.https://www.infoq.com/presentations/Value-Objects-Dan-Bergh-Johnsson
11.https://www.nginx.com/blog/event-driven-data-management-microservices/
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
