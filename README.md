# Document
Contains important documents for reference

# Important Links
https://discuss.pivotal.io/hc/en-us/categories/200072648-Pivotal-Cloud-Foundry-Knowledge-Base

*Spring dependency management outline*: https://gist.github.com/tygern/7ae839d0165e7f2bd141402654dc8966

*Spring Cloud dependency chart*: https://docs.pivotal.io/spring-cloud-services/common/client-dependencies.html

*PAL links*: https://platform-acceleration-lab-links-v1.cfapps.io/

# Debug in PCF
This is the three steps which we need to follow to debug a PCF application:
1) cf set-env spring-music JBP_CONFIG_DEBUG '{enabled:true}'
2) Create an SSH tunnel: cf ssh -N -T -L <localport>:localhost:<remote port> spring-music
3) Go to Intellij and setup a remote debug profile. Give the localhost post in the dialog box.

