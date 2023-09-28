# vendor_xiaomi_sunny-firmware

Firmware images for Redmi Note 10 (sunny), to include in custom ROM builds.

**Current version**: 

### How to use?

1. Clone this repo to `vendor/xiaomi/sunny-firmware`

2. Include it from `BoardConfig.mk` in device tree:

```
# Firmware
-include vendor/xiaomi/sunny-firmware/BoardConfigVendor.mk
```

