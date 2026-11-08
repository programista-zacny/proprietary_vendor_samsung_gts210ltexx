# Proprietary files for the Samsung Galaxy Tab S2 9.7 LTE (SM-T815, gts210ltexx)

Vendor blobs for the LineageOS 24.0 (Android 17) Wi-Fi only build of
[gts210ltexx-patches](https://github.com/programista-zacny/gts210ltexx-patches) (branch
`lineage-24.0`): Broadcom Wi-Fi and Bluetooth firmware and NVRAM files, the GPS daemon and HAL,
the sensors HAL, and Trustonic TEE trustlets (`mcRegistry`). `gts210ltexx-vendor.mk` adds every
file under `proprietary/` to `PRODUCT_COPY_FILES`.

Use: clone this repository into the gts210ltexx-patches checkout, where
`scripts/prepare-tree.sh` copies it to `vendor/samsung/gts210ltexx` in the LineageOS tree:

    git clone -b lineage-24.0 https://github.com/programista-zacny/proprietary_vendor_samsung_gts210ltexx vendor/gts210ltexx

Origin: not recorded; see the device tree README in gts210ltexx-patches
(`device/gts210ltexx/README`). 43 of the 49 files under `proprietary/` are identical to the
gts210wifi and gts2-common files in rINanDO's
[proprietary_vendor_samsung](https://github.com/rINanDO/proprietary_vendor_samsung).

The files under `proprietary/` are the property of Samsung, Broadcom and Trustonic. They are
redistributed as they are, which is common for LineageOS device bring-ups, and will be removed on
request of the rights holder. No license is granted for them by this repository. The two
makefiles carry their own Apache License 2.0 headers.
