Let's run our first container

Pull a hello-world image:
~~~
docker pull hello-world
~~~

Run the image:
~~~
docker run hello-world
~~~

If the image is not present on the host when executing the command, docker will pull it from docker hub before attempting to run it. Otherwise it will run the image already present.

This will display a *Hello from Docker!*
