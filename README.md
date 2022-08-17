# Reproduction Instructions

1. `yarn`
1. `yarn build`

Result:

```
 ERROR  'request' is not exported by __vite-browser-external, imported by node_modules/@aws-sdk/credential-provider-node/node_modules/@aws-sdk/credential-provider-imds/dist/es/remoteProvider/httpRequest.js
file: /Users/samh/Code/repro-vite-aws-sdk/node_modules/@aws-sdk/credential-provider-node/node_modules/@aws-sdk/credential-provider-imds/dist/es/remoteProvider/httpRequest.js:4:9
2: import { ProviderError } from "@aws-sdk/property-provider";
3: import { Buffer } from "buffer";
4: import { request } from "http";
            ^
5: /**
6:  * @internal
```
