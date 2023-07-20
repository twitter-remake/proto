# Shared Protocol Buffers Contracts

This repository contains the shared protocol buffers contracts for every service in the system. Each proto file must not be in any of the service repositories, but instead in this repository. We use [git submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules) to include this repository in each service repository.

## Contribution

We use [buf](https://buf.build/) to lint and generate the code from the proto files. Please install it before contributing.