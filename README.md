# seciotcrgb

The combination of the ADS7846 touchscreen alongside spidev1.0 (SPI1) was
required for this project. This combination was unsupported by existing
overlays so I made a new one to support it and uploaded it here.

## Installing
From the Raspberry Pi:
```
git clone https://github.com/harlanw/seciotcrgb
make install
```

Do not forget to update your `config.txt` file. An example config has been
included for reference.

## Board Render

![seciotcrgb](https://sites.google.com/a/oregonstate.edu/ece44x201830/_/rsrc/1543258997867/ece-senior-design-example-project/Chess%20Board%20Render.png "seciotcrgb 3D render")
