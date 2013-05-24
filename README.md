appengine-servers-sample-java


It has 2 web apps each deployed to a different server: guestbook and shardedcounter.

Usage (After changing the app id in the appengine-servers-ear/src/main/application/META-INF/appengine-application.xml):

    git clone https://github.com/ludoch/appengine-servers-sample-java.git
    cd appengine-servers-sample-java
    mvn install
    cd appengine-servers-ear
    #to test it locally:
    mvn appengine:devserver
    #or to deploy it:
    mvn appengine:update

=============================
