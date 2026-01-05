This file contains details steps for Running JDK on Docker.

Choose image_id which runs on multiple platform.
Step 1) docker search openjdk:<image_id> 

Step 2) docker pull openjdk:22-jdk

Step 3) docker run -it openjdk

It will execute the container. And provide us the jshell.

JShell is an interactive Java shell (REPL) that lets you write and run Java code line by line, without creating a full Java program.
