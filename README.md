# Java-Snake-Game
Java Snake game source code

https://zetcode.com/javagames/snake/  

![Snake game screenshot](snake.png)

# To run podman 
podman run -it \
  --name java-snake-game \
  -e DISPLAY=:0 \
  -v /tmp/.X11-unix:/tmp/.X11-unix:rw \
> docker.io/bidweavinash4176/java-snake-game:01
