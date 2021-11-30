# ros2 cyclonedds iceoryx shared memory demo

This is a simple talker/listener demo using shared memoery

## Usage

### Note: 
These instructions assume you want 10 talkers and 10 listeners, scale back or up accordingly

Without shared mem:
`docker-compose -f docker-compose.yaml up --scale ros2-talker=10 --scale ros2-listener=10`

With shared mem:
`docker-compose -f docker-compose.yaml -f roudi.override.docker-compose.yaml up --scale ros2-talker=10 --scale ros2-listener=10`

Reference
  - https://github.com/ros2/rmw_cyclonedds/blob/master/shared_memory_support.md
  - https://github.com/eclipse-iceoryx/iceoryx/tree/master/iceoryx_examples/icedocker

