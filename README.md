# RealOrCake

A 3D birthday cake for Poopu. Turn on the camera and mic, make a wish, and blow the candles out for real.

## Run it

Serve the folder locally, then open http://localhost:8765 and allow camera and mic access:

```bash
python3 -m http.server 8765
```

Camera and mic only work on `localhost` or over https (for example, GitHub Pages).

No mic? Tap the flames or hold Space to blow them out.

Built with three.js. It needs an internet connection, because three.js and the fonts load from a CDN.
