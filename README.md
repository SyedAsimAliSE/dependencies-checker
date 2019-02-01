# To check dependencies versions.

I use [buildSrc](https://docs.gradle.org/current/userguide/organizing_gradle_projects.html#sec:build_sources) to abstract imperative logic, 
but it won't tell the new versions like it tells in project level build files. So this project contains all the common libs i use in my projects
to get updates, i check it every month and then update the projects.

it's bit of manual labour but i like buildSrc :)
