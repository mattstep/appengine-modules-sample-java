appengine-modules-sample-java


It has 2 web apps each deployed to a different module: guestbook and shardedcounter.

Change the app id in the [appengine-application.xml](appengine-modules-ear/src/main/application/META-INF/appengine-application.xml).

Notice the new &lt;server&gt; entry in [appengine-web.xml](appengine-modules-guestbook/src/main/webapp/WEB-INF/appengine-web.xml)

Usage:
    git clone https://github.com/ludoch/appengine-modules-sample-java.git
    cd appengine-modules-sample-java
    mvn install
    cd appengine-modules-ear
    #to test it locally:
    mvn appengine:devserver
    #or to deploy it:
    mvn appengine:update

=============================
