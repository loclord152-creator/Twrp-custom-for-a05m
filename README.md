# A055 TWRP Device Tree

Custom TWRP recovery device tree for Samsung Galaxy A05m (MT6768 chipset)

## Project Info

- **Device**: Samsung Galaxy A05m
- **Chipset**: MediaTek MT6768
- **TWRP Version**: Compatible with latest TWRP source
- **Base**: Samsung Galaxy G85 device tree + physwizz TWRP configs

## Structure

```
├── device/              # Device tree configurations
│   ├── BoardConfig.mk   # Device specifications & build configs
│   ├── recovery.fstab   # Partition layout
│   ├── device.mk        # Device properties
│   └── twrp.flags       # TWRP recovery settings
├── kernel/              # Kernel source (to be cloned)
├── docs/                # Documentation
├── MERGE_NOTES.md       # Merge strategy documentation
└── README.md            # This file
```

## Quick Start

```bash
# Clone this repository
git clone https://github.com/loclord152-creator/Twrp-custom-for-a05m.git device_tree_a055
cd device_tree_a055

# Clone kernel source
git clone https://github.com/Theman-Fromfar/a05m-kernel-6.6 kernel/samsung/mt6768

# Follow build instructions
cat docs/BUILD_INSTRUCTIONS.md
```

## Requirements

- TWRP source code
- MediaTek kernel source
- Linux build environment
- 50GB+ disk space

## Building

See `docs/BUILD_INSTRUCTIONS.md` for detailed build instructions.

## Contributors

- Based on Samsung Galaxy G85 device tree
- TWRP configs adapted from physwizz

## License

Follow original source repositories licenses.