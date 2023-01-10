# Bunker Base2
ROS2 driver for Bunker base with dynamic covariances added and battery status

To build into a production environment. Run the following commander  
```bash
DOCKER_BUILDKIT=1 docker build -f bunker_base2/Dockerfile_dev -o out_bunker_base2 .
```
Then to create the production container, run
```bash
docker build -t bunkerbase2:prod -f bunker_base2/Dockerfile_prod .
```
