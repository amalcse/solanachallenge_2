# Metaplex Candy Machine Reference UI

## Remove Slope (scam) wallet

See [soladex report](https://soladex.io/project/slope-wallet-scam/) describing the issue.

## OpenSSL error

If you encounter the error below, you'll need to run `export ENV NODE_OPTIONS="--openssl-legacy-provider"`

```
  opensslErrorStack: [ 'error:03000086:digital envelope routines::initialization error' ],
  library: 'digital envelope routines',
  reason: 'unsupported',
  code: 'ERR_OSSL_EVP_UNSUPPORTED'
```
