HTalk
=====

[![Build Status](https://travis-ci.org/eric-leblouch/htalk.svg?branch=master)](https://travis-ci.org/eric-leblouch/htalk)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/02f03a74561649aaa9d033ce94eca6c3)](https://www.codacy.com/app/eric-leblouch/htalk?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=eric-leblouch/htalk&amp;utm_campaign=Badge_Grade)

Build
-----

Need sbt 0.13 or higher for the sbt eclipse command

To build the toplevel project and all its sub-projects:

    $ sbt compile


Test
----

    $ sbt test

You need to create a hbase-site-`username`.properties in `src/test/resources` pointing to your HBase instance
to test the application you can use the
[hfactory-server-in-docker-machine](https://github.com/hfactory/hfactory-server-in-docker-machine)
project to launch your local standalone HBase instance. Use the `hfactory-env.sh` startHBase command.
