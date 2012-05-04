Scala on MSYS
=============

Enable Scala on MSYS.

A normal Scala installation doesn’t work well together with MSYS/MinGW/Git
for Windows. This repository contains modified scripts of the current Scala
version that allow you to use Scala (including SBT) in the MSYS bash.


Getting started
---------------

Simply clone this repository with

    git clone git://github.com/pvorb/scala-on-msys.git

or
[download the latest ZIP file](https://github.com/pvorb/scala-on-msys/tags)
and unzip it. Then add the directory where you cloned or unpacked the files to
your system `PATH`.

For using SBT,
[download the latest `sbt-launch.jar`](http://typesafe.artifactoryonline.com/typesafe/ivy-releases/org.scala-tools.sbt/sbt-launch/)
and move it to the same directory as the scripts.

You should now be able to use `scala`, `scalac`, `scalap`, `scaladoc`, `fsc` and
`sbt` from any directory in a MSYS bash window.


Older versions of Scala
-----------------------

There’s support as of Scala 2.9.2. Every supported Scala version will get a tag.
If you want to use an older version of Scala, you can download an older version
of the scripts in the
[tags section](https://github.com/pvorb/scala-on-msys/tags).
