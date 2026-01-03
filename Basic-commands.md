This file contains the basic docker commands.

Note: hello-world is the image name.

### 1. Search the image
```
docker search hello-world
```
It will list down all the images. Remember, image for which Official = OK means it is an official image.

### 2. Pull the image
```
docker pull hello-world
```
It will download the image from the registry

### 3. Create the container
```
docker create hello-world
```
It will create the container of hello-world image.

### 4. Start the container
```
docker start <container-id>
```
It will run the container.

### Important Note: 
```docker run <container-id>``` command can perform all the above mentioned step in one go.

### Other important commands
```docker stop <container-id> ``` - It will stop the container.

```docker pause <container-id> ``` - It will pause the container.

```docker rm <container-id> ``` - It will delete the container.

```docker rmi <image-id> ``` - It will delete the image.

Always remember to delete the container first.
