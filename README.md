[![CircleCI](https://circleci.com/gh/modusbox/mojaloop-sdk-standard-components/tree/master.svg?style=svg&circle-token=3a545ba78f7989a312b177e60095c658e1349383)](https://circleci.com/gh/modusbox/mojaloop-sdk-standard-components/tree/master)

# Mojaloop DFSP SDK Standard Components

This package contains a set of  components that encode standard practices for enabling the following features of a DFSP to Mojaloop switch interface:

## Usage

```
npm install @modusbox/mojaloop-sdk-standard-components
```

 1. JWS (JSON Web Signature) - For signing and signature verification
 2. Interledger Protocol - For generating and verifying Interledger message content
 3. Mojaloop Requests - An abstration that simplifies making HTTP requests to Mojaloop API compliant peers demonstrating specification compliant HTTP header handling and JSON Web Signatures
 4. Errors - Mojaloop API specification compliant error helpers

For an example usage of these components please see the Mojaloop SDK Scheme Adapter available [here](http://www.github.com/modusbox/mojaloop-sdk-scheme-adapter).

For information on the background and context of this project please see the presentation [here](docs/Mojaloop%20-%20Modusbox%20Onboarding%20functionality.pdf)


