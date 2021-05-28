
## QR Code scanner for login hotspot MikroTik

### 

1. Copy and paste at login.html
```html
<button onclick="window.location='https://lupael.github.io/myqr/?hotspot=SpeedLinks';">QR Code</button>
```
2. Paste following code in MikroTik via Terminal.
```
/ip hotspot walled-garden ip

add action=accept comment="i4E QR Code Scanner" disabled=no dst-host=https://lupael.github.io
```

### Powered by i4e.com.bd
