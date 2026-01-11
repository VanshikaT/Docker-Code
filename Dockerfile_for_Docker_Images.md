DockeFile is used to automate the running of the images.

1. Create a DockerFile:-
   

    FROM openjdk:22-jdk
  
    ADD target/docker-demo.jar docker-demo.jar

    ENTRYPOINT ["java", "-jar", "/docker-demo.jar"]



2. Below are the steps to build the Image:-
   
   docker build -t dockerdemo:v4 .

  

Here, -t = to define the tag name.

      . = to create the image in the same repository.

3. Run the image:-
   
   docker run -p 8080:8080 dockerdemo:v4

