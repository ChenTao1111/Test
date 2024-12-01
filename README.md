
## Architecture

The server is based on Boost.Beast, asynchronous (it uses stackful coroutines)
and single-threaded. It requires C++17 to build. It uses Redis and MySQL for
persistence.

The client is web-based and uses Next.js. It communicates with the server
using websockets.

You can read more about the architecture
[in this section of the docs](https://anarthal.github.io/servertech-chat/01-architecture.html).

