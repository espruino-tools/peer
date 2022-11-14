
![version](https://img.shields.io/npm/v/@espruino-tools/peer)
![build](https://img.shields.io/azure-devops/build/espruino-tooling/Espruino%2520tools/16)
![deployment](https://img.shields.io/azure-devops/build/espruino-tooling/Espruino%2520tools/18?color=blue&label=deployment)

# @espruino-tools/peer

## Data

```javascript
import { Host } from "@espruino-tools/peer";

let p = new Host("other device domain");

p.getData(function (data) {
  /*
        code to handle data 
    */
});
```

```javascript
import { Connector } from "@espruino-tools/peer";

let p = new Connector();

p.connectData(function (data) {
  /* callback on connect */
});
```

## Video

```javascript
import { Host } from "@espruino-tools/peer";

let p = new Host("other device domain");

p.getVideo(function (data) {
  /*
        code to display video 
    */
});
```

```javascript
import { Connector } from "@espruino-tools/peer";

let p = new Connector();

p.connectVideo();
```
