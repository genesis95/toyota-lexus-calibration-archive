# Toyota / Lexus Calibration Archive

A community-maintained archive of Toyota and Lexus ECU calibration files, organized by calibration ID.

---

## Folder Structure

```
BIN/
  ├── Toyota/
  │     ├── <Model>/
  │     │     └── <Model + Engine>/
  │     │           └── <Calibration ID>/
  │     │                 └── <Calibration ID>.bin
  │     └── BIN/
  │           └── <Calibration ID>/       ← unsorted (no vehicle match found)
  │                 └── <Calibration ID>.bin
  └── Lexus/
        ├── <Model + Engine>/
        │     └── <Calibration ID>/
        │           └── <Calibration ID>.bin
        └── BIN/
              └── <Calibration ID>/       ← unsorted (no vehicle match found)
                    └── <Calibration ID>.bin
```

**BIN** files are raw binary ECU images organized by brand and vehicle model.  
**CUW** files are Toyota's proprietary calibration update format and are not included in this repo due to size.

---

## Calibration ID Format

| Pattern | Example | Notes |
|---------|---------|-------|
| 10-digit `89xxx` | `89663-02001` | Standard single-ECU cal — hyphen inserted at position 5 |
| 8-digit | `34218200` | Non-`89` cal reference |
| 12-digit `89xxx` | `899834825300` | Extended / dual-ECU cal — no hyphen added |

---

## Contributing

1. Fork the repo and create a branch named after the calibration ID (e.g. `89663-02001`).
2. Place your file(s) in the correct folder following the structure above.
3. Open a pull request — include the vehicle application (year / model / engine) in the PR description.

To organize a local collection of raw files into this structure automatically, use the companion organizer script:  
[`organize_calibration.py`](https://github.com/genesis95/toyota-lexus-calibration-archive/releases) *(see Releases)*

---

## Supported Vehicles

Calibrations in this archive cover Toyota and Lexus vehicles including (but not limited to):

- Tacoma
- Tundra
- 4Runner
- Land Cruiser / Prado
- Sequoia
- Camry / Avalon
- RAV4 / Highlander
- IS / GS / LS / GX / LX

---

## Disclaimer

These files are provided for educational and research purposes.  
Always verify a calibration ID is correct for your specific vehicle before use.  
Improper ECU calibration can cause drivability issues or hardware damage.  
This archive is not affiliated with or endorsed by Toyota Motor Corporation.
