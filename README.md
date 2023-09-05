# Chrome-Edge-in-KIOSK-mode
Chrome &amp; Edge Browser in KIOSK

Run shell:startup and copy example shortcuts with below actions


```
-- Chrome
"C:\Program Files\Google\Chrome\Application\chrome.exe" --kiosk http://127.0.0.1:1010/ --disable-web-security --fullscreen --incognito --disable-pinch --overscroll-history-navigation=0
```


```
-- Edge
"C:\Program Files (x86)\Microsoft\Edge\Application\msedge.exe" --kiosk http://127.0.0.1:1010/  --edge-kiosk-type=fullscreen --no-first-run
```
