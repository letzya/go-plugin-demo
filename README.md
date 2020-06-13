
# Go plugin demo

## For Tyk version v2.9.3 mount pwd to "plugin-build"
docker run --rm -v `pwd`:/go/src/plugin-build tykio/tyk-plugin-compiler:v2.9.3 my-plugin-293.so

## For Tyk version v2.9.4.1 mount to "plugin-source"
docker run --rm -v `pwd`:/plugin-source tykio/tyk-plugin-compiler:2.9.4.1 my-go-plugin-2941.so
