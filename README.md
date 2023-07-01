# nodejs-web-express-api-basic-auth-ssl-hello-world

## Description
A expressjs api that uses basic authentication
and self signed ssl.

| username | password |
| -------- | -------- |
| *maria* | *pass* |

Features: 
- basic authentication
- self signed ssl

## Tech stack
- expressjs

## Docker stack
- alpine:edge
- node:latest

## To run
`sudo ./install.sh -u`
- curl -i -k https://localhost/ -u 'maria:pass'

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Express ssl code](https://dev.to/omergulen/step-by-step-node-express-ssl-certificate-run-https-server-from-scratch-in-5-steps-5b87)