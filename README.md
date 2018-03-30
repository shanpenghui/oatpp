# oat++

Zero-Dependency. Performance oriented web-service-development framework.
Organic. Pure C++.

## Features

- Blazingly fast
- Zero Dependency, no installations
- **Asynchronous server (High performance. Handle 30K+ simultaneous connections)**
- Multithreaded server (Simple API)
- Connection agnostic. (Use whatever transport. Whatever SSL backend. Whatever sockets, pipes, files. etc. It cares about HTTP stream only)
- REST framework
- Retrofit-like client wrapper (Use whatever request executor for example cURL, or minimalistic one provided out of the box)
- Object mapping (Fast object serialization-deserialization. Currently JSON, more formats comes shortly)
- Simple dependency injection framework
- Simple Test framework
- HTTP_1.1 (2.0 comes shortly)

## How to start

Grab any project from [examples](https://github.com/oatpp/oatpp-examples), and follow README

### Examples:

- [CRUD](https://github.com/oatpp/oatpp-examples/tree/master/crud) - Example project of how-to create basic CRUD endpoints
- [AsyncApi](https://github.com/oatpp/oatpp-examples/tree/master/AsyncApi) - Example project of how-to use asynchronous API for handling large number of simultaneous connections
- [ApiClient-Demo](https://github.com/oatpp/oatpp-examples/tree/master/ApiClient-Demo) - Example project of how-to use Retrofit-like client wrapper (ApiClient) and how it works
