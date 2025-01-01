# devcontainer-cuda

Remove devcontainer for golang cuda development

## Development log

### Ollama

This is a set of commands to get an ollama dev environment working

```bash
$ apt-get update
$ apt-get install git
$ curl -OL https://go.dev/dl/go1.23.4.linux-amd64.tar.gz
$ rm -rf /usr/local/go && tar -C /usr/local -xzf go1.23.4.linux-amd64.tar.gz
$ export PATH=$PATH:/usr/local/go/bin
$ go version
$ apt-get install make gcc g++
$ clone https://github.com/allenporter/ollama
$ OLLAMA_DEBUG="1" OLLAMA_HOST=0.0.0.0 ./ollama serve
```
