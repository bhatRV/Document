# Document
Contains important documents for reference

## Important Links
```
1.https://discuss.pivotal.io/hc/en-us/categories/200072648-Pivotal-Cloud-Foundry-Knowledge-Base
2.https://gist.github.com/tygern/7ae839d0165e7f2bd141402654dc8966
3.https://docs.pivotal.io/spring-cloud-services/common/client-dependencies.html
4.https://platform-acceleration-lab-links-v1.cfapps.io/
5.http://cloud.rohitkelapure.com/2016/10/snap-analysis-of-applications.html
```

### Debug in PCF
This is the three steps which we need to follow to debug a PCF application:
```
1) cf set-env spring-music JBP_CONFIG_DEBUG '{enabled:true}'
2) Create an SSH tunnel: cf ssh -N -T -L <localport>:localhost:<remote port> spring-music
3) Go to Intellij and setup a remote debug profile. Give the localhost post in the dialog box.
```

