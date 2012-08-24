angular-jstd-gradle
===================

what?
-----

Using [angular-seed](http://github.com/angular/angular-seed) as a base, this project includes a simple gradle build script that includes a task to run unit and e2e tests.

why?
----

We are using gradle and angular on a project. It seemed sensible to create a reusable, barebones project where these guys play nice together.

It might help us and hopefully others to get a project up and running in the future.

how?
----

There are only two changes to the base angular-seed. We've included a different version of the JSTD jar as the one supplied didn't seem to have a require class. We've also obviously added build.gradle containing the task.

To run it use the command:
> gradle jstd

nb. It doesn't start up any web server. Without this the e2e tests will fail.



Sure there are some improvements that can be made to this but it should get things started.