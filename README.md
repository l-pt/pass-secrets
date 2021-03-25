# pass-secrets
CLI Application that provides the Freedesktop Secret Service using Pass as its backend!

## Status
Currently working to store secrets with protonmail-bridge. I have not done tests with other applications; if it doesn't work, please open an issue!

## How to build
pass-secrets requires pass and sdbus-c++ to be installed on your machine. Rapidjson and nanoid are included in the repo.

```
cd pass-secrets
mkdir build
cd build
cmake ..
make
```

The binary generated can be installed anywhere.
