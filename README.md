# for zopfli

```
git clone https://github.com/google/zopfli.git zopfliDir
cd zopfliDir
make
./zopfli ***
```


# memo for docker

```
docker run --name my-custom-nginx-container \
  -v $(pwd)/other.conf:/etc/nginx/conf.d/default.conf:rw \
  -v $(pwd)/fuga:/etc/nginx/fuga:rw \
  -p 80:80 -d nginx
```
