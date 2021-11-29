# ros2 cyclonedds iceoryx shared memory demo

This is a simple talker/listener demo using shared memoery

## Usage
`docker-compose up`

## Notes
**Note**: unfortunately the iceoryx container is not on dockerhub or any other registry, so right now the docker-compose builds the underlying container as well, which requires internet connection as well as time. 

To rebuild after changing
`docker-compose up --rebuild`

Reference
  - https://github.com/ros2/rmw_cyclonedds/blob/master/shared_memory_support.md


