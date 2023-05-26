# i8080: an Intel 8080 emulator

This is heavily modified from the original version [go-i8080](https://github.com/GinjaNinja32/go-i8080) please see that repo for the original code.

### Details

- BIOS-level emulation of CP/M
- Disk support (somewhat hardcoded, see `diskio.go`)
- Can run CP/M 2.2 (see `example/` folder)

### TODOs and limitations

- Disk format is currently hardcoded
- Instruction dispatch could probably be optimised
- Split Run() into Run() and Step(), to allow per-instruction stepping
