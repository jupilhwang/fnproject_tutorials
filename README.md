# [Fn - http://fnproject.io/](https://github.com/fnproject)
- 2017.12.19
- @jupil.hwang

## Fn Project
- a lightweight Docker-based serverless functions platform you can run on your laptop, server, or cloud

fnproject tutorials
https://github.com/fnproject/tutorials/tree/master/Introduction

# Fn cli
## Install
- homebrew : macOS
  ```bash
  brew install fn
  ```
- shell script (linux or others)
  ```bash
  curl -LSs https://raw.githubusercontent.com/fnproject/cli/master/install | sh
  ```
- Download the bin
  binary download [relaese](https://github.com/fnproject/cli/releases) and Download it

## Start
fn을 시작하기 위해서 fnproject/functions 와 fnproject/ui의 Docker Image를 시작한다
  ```bash
  # Fn server
  fn start

  # Fn-UI server
  docker run --rm -it --link functions:api -p 4000:4000 -e "API_URL=http://api:8080" --name fn-ui fnproject/ui
  ```
  --> Local Docker Server에서 Container가 기동한다.


# Fn Go
Fdk-go https://medium.com/fnproject/fn-easy-functions-for-go-b32a28e0f012


# Announcing JAX-RS support for Fn Project
https://medium.com/fnproject/announcing-jax-rs-support-for-fn-project-4a66ff34118f

# New JSON Hot Function Format
https://medium.com/fnproject/new-json-hot-function-format-f6b8cd5876c7

# Fn Project Helm Chart for Kubernetes
https://medium.com/fnproject/fn-project-helm-chart-for-kubernetes-e97ded6f4f0c

# Flow
## Flow 101
https://medium.com/fnproject/flow-101-be7f328ffce2

## Flow 102
https://medium.com/fnproject/flow-102-9fb94134bea9

