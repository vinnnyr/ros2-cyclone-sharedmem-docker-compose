# ros2 cyclonedds iceoryx shared memory demo

This is a simple talker/listener demo using shared memoery

## Usage

Without shared mem:
`docker-compose -f docker-compose.yaml up`

With shared mem:
`docker-compose -f docker-compose.yaml -f roudi.override.docker-compose.yaml up`

Reference
  - https://github.com/ros2/rmw_cyclonedds/blob/master/shared_memory_support.md
  - https://github.com/eclipse-iceoryx/iceoryx/tree/master/iceoryx_examples/icedocker

