# READ THIS

## if you choose to build this firmware with qmk, be aware that the rev1/keyboard.json F7 has been changed to D4. This is due to an arduino pin malfunction. If you decide to build, change this back to F7

**no change**

```json

    "matrix_pins": {
        "cols": ["F6", "F7", "B1", "B3", "B2", "B6"],
        "rows": ["C6", "D7", "E6", "B4", "B5"]
    },

```

**A0 to D4 change**

```json

    "matrix_pins": {
        "cols": ["F6", "D4", "B1", "B3", "B2", "B6"],
        "rows": ["C6", "D7", "E6", "B4", "B5"]
    },

```
