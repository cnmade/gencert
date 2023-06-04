# Gencert

This is tool generate tls cert for your server.
it is from :  [https://go.dev/src/crypto/tls/generate_cert.go](https://go.dev/src/crypto/tls/generate_cert.go)

You can install it from 
```bash
go install github.com/cnmade/gencert@master
```


## Usage

To use gencert to generate your cert

you need to run 

```bash
./gencert -host=pandas.dev.com 
```

the host argument is the host name of the certs will match.
