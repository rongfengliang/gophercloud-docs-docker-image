# wget for mirrorgophercloud docs

## cmd

```code
wget -mkEpnp http://gophercloud.io/
```

## docker image

```code
docker build -t dalongrong/gophercloud-docs .
```

## runing

```code
docker run -d -p 80:80 dalongrong/gophercloud-docs
```