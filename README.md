<h1>Scan QR Code Web RTC</h1>

- Necessário `https` para funcionar no dispositivo.

- Para funcionar na camera trazeira do IOS no arquivo `video.js` utilizar o seguinte:

```js
var constraints = {
    video: {
      facingMode: "environment",
      mandatory:{
        maxWidth: mobileVideoWidth,
        maxHeight: mobileVideoHeight,
      }
      // deviceId: {exact: videoSelect.value}
    }
  };
```

- [Back Camera on mobile - SOLVED!](https://github.com/jeromeetienne/AR.js/issues/86)