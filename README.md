# ix2-dl
Flattened device tree (FDT) to make custom linux or BSD kernels run on Iomega/Lenovo/EMC ix2-**dl** (sold without HDDs, contains 1GB NAND). [^1] [^2]

- kirkwood-lenovo-ix2-common.dtsi: Marvell Kirkwood platform common device tree from linux source tree (for reference)
- kirkwood-lenovo-ix2-dl.dts: ix2-dl NAND definition *(partitions can be modified here if needed!)*
- kirkwood-lenovo-ix2-dl-full.dts: merged ix2-dl device tree in one file
- kirkwood-lenovo-ix2-dl-stock.dtb: binary device tree ready for deployment on device
- kirkwood-lenovo-ix2-ng.dts: ix2-**ng** flash definition **(NOT NAND!)** (for reference, (c) Daniel Helgason @ [Linux Device Hacking forum](https://forum.doozan.com/read.php?3,19216))

# mtd0
mtd0 partition (u-boot bootloader) backup for emergency rescue if you manage to wipe it.

# docs
Bootlogs and documentation for reference (c) Daniel Helgason @ [Linux Device Hacking forum](https://forum.doozan.com/read.php?3,19216)

[^1]: [wikidevi device info mirror](https://wikidevi.wi-cat.ru/Iomega_StorCenter_ix2-dl)
[^2]: [nas-central device info mirror](https://web.archive.org/web/20190423102938/https://iomega.nas-central.org/wiki/Category:Storcenter_ix2-dl)
