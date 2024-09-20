# qrcode terminal for macos
Decode QR code on screen, or encode a string then echo QR code on terminal for MacOS.

## Usage

### Decode

Run `qrcode` in terminal, use mouse to select QR code area on screen.

```
$ qrcode
```

### Encode

```
$ qrcode "sample string"
```

## Dependencies

- screencapture (for macos: /usr/sbin/screencapture)
- zbarimg (homebrew)
- qrcode-terminal (npm)

### Installation

1. npm -g install qrcode-terminal
2. brew install zbar