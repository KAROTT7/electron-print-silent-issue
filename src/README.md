# electron-print-silent-issue

electron version: 26.0.0-alpha.7

```
System:
  OS: macOS 13.4
  CPU: (8) arm64 Apple M1
  Memory: 125.50 MB / 16.00 GB
  Shell: 5.9 - /bin/zsh
Binaries:
  Node: 18.16.0 - /opt/homebrew/opt/node@18/bin/node
  Yarn: 1.22.19 - /opt/homebrew/bin/yarn               <- used
  npm: 9.5.1 - /opt/homebrew/opt/node@18/bin/npm
Browsers:
  Chrome: 114.0.5735.133
  Safari: 16.5
```

### reproduce
- yarn start
- click button
- then output error `[13903:0620/134749.492708:ERROR:print_render_frame_helper.cc(2339)] Printing failed.` in console

