# Client-server model with multiplexing
This is an educational project, aimed at understanding how to interact with platform-specific multiplexing APIs (epoll) to implement a more performant client-server architecture.

## Build
```
$ mkdir build
$ cd build
$ cmake ..
$ make
```
Requires C++14 compiler.

## Usage
Run server:
`$ ./os-net-multiplexing-server <port>`

Run client:
`$ ./os-net-multiplexing-client <port>`

  
## Test
Tested manually on Linux 4.12.

## Copyright
Pavel Ponomarev, 2019 (pavponn@gmail.com)

MIT License.
