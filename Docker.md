
<image-name><-- which is stored in dockerhub
:tag<---------- version no. of images, this is optional.
To pull docker images form docker hub, we can use 

    $docker pull <docker-image:tag>
To run the image we can use the conmmand:

    $docker run <image-name:tag> or $docker run <image-id>
 To list down all images in our system, we can give the command:
 
    $docker images
 To list down all running container:
 
    $docker ps
 To list down all containers(even its running or not):
    
    $docker ps-a
