# About this repo
This is custom docker container Image for http-echo of hashicorps(https://github.com/hashicorp/http-echo)


# Install image
```
docker pull p3nguin224/hc-http-echo:1.0
```

# Instruction
The default port is 8899 and the default text to display is 'hello world'
-listen=:8899 
-text="hello world"

```
docker run -p 80:80 --name test-echo -d hc-http-echo:1.1 -listen=:80 -text="Hello Sky!!!"
```