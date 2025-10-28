# Omnicon

Omnicon is a controller for everything. Although its not a controller in the
first place. Omnicon actually combines a [8BitDo Zero 2 Controller][zero2] as
the input device and an [ESP32-WROOM-32][esp32] as the chip that actually does
the heavy-lifting for other actions.

## Why?

I always wanted a retro controller that can do *almost* anything. Of course I
could use my phone, but where's the fun in it? Also, I want to learn Rust while
working in embedded systems, and this project seems like the perfect fit.

## Roadmap

- [ ] Plugin system to add actions
- [ ] Emulated layers through the ESP32
- [ ] Raspberry Pi support

<!-- References -->
[zero2]: https://www.8bitdo.com/zero2/
[esp32]: https://documentation.espressif.com/esp32-wroom-32_datasheet_en.pdf
