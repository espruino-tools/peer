# Espruino Tools -> Peer

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
