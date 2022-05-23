# How to take page screenshot in specific resolution

```bash
google-chrome --headless --screenshot="screen.png" -window-size=1280,720 "https://github.com"
```

- `--screenshot` - make screenshot and save it to specified file
- `--headless` - will launch chrome in [headless mode](https://developers.google.com/web/updates/2017/04/headless-chrome#cli)
- `-window-size` - set browser window size
- `1280,720` - opens browser in `1280x720` size
- `github.com` - url to open

group: screenshot


