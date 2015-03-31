## Spring Boot Support in IntelliJ IDEA 14.1 webinar

This is the sample application used for Spring Boot Support in Intellij IDEA 14.1 webinar.

It provides a very simple entity (`Speaker`) with a repository (`SpeakerRepository`) backed by an in-memory database (H2). The repository is exposed as a  _REST_ endpoint.

Look at the `application.properties` to see the various customizations. You will need to login as `user` / `changeme`. Look at the `security.user.password` property for more details.
 
There is also a `Dev` profile you can enable via the _Run_ configuration that exposes the H2 console and disable security altogether.
 
Finally, this app showcase how you can use the annotation processor to generate the relevant meta-data for your own keys and have content assistance right from Intellij IDEA! Check `HelloProperties` and the `pom.xml` for more information.

