 Toyota / Lexus Calibration Archive

A community-maintained archive of Toyota and Lexus ECU calibration files (`.bin`), organized by brand and vehicle.

---

## Finding a File

Browse by vehicle model or search by calibration ID using GitHub's search bar.

```
BIN/
├── Lexus/
│     └── Lexus [Model] [Engine]/
│           └── [Calibration ID]/
│                 └── [Calibration ID].bin
│
├── Toyota/
│     └── [Model]/
│           └── [Model] [Engine]/
│                 └── [Calibration ID]/
│                       └── [Calibration ID].bin
│── Unsorted/
      └── [Calibration ID]/        ← files without a confirmed vehicle match
            └── [Calibration ID].bin
```

**Examples:**
- `BIN/Lexus/Lexus ES250 2.5 2ARFE/89663-33F41/89663-33F41.bin`
- `BIN/Toyota/Camry/Camry 2.4 2AZFE/89663-33561/89663-33561.bin`

---

## Contributing

1. Fork the repo and create a branch named after the calibration ID.
2. Place your file following the folder structure above.
3. Open a pull request — include year, model, and engine in the description.

---

## Supported Vehicles

Calibrations in this archive cover Toyota and Lexus vehicles including (but not limited to):

**Toyota:** Tacoma, Tundra, 4Runner, Land Cruiser (LC100/120/150/200), Sequoia, Camry, Avalon, RAV4, Highlander, Corolla, Prius, HiLux, Fortuner, HiAce, FJ Cruiser, Venza, Yaris

**Lexus:** IS, GS, ES, LS, GX, LX, RX, SC

---

## Disclaimer

These files are provided for educational and research purposes.
Always verify a calibration ID is correct for your specific vehicle before use.
Improper ECU calibration can cause drivability issues or hardware damage.
This archive is not affiliated with or endorsed by Toyota Motor Corporation.
