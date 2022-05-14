# groovy-cli-bazel-crypto-des-encrypted-bcrypt-encoded

## Description
Encrypt and decrypt password with DES
encoded with bcrypt.

When storing a password it is best practice
to use a one-way hash such as bcrypt, scrypt,
or argon2.

## Tech stack
- groovy
- bazel
  - des
  - bcrypt

## Docker stack
- l.gcr.io/google/bazel

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
