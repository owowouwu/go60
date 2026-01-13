Go60 with dongle concept. Currently using [YADS](github.com/janpfischer/zmk-dongle-screen).

Steps to flash:
1. Build firmware with actions.
2. Flash dongle with settings reset firmware and `go60_dongle.uf2`
3. Settings reset both halves of Go60 according to the [instructions here](https://docs.moergo.com/go60-user-guide/troubleshooting/#configuration-factory-reset-and-re-pairing-left-and-right-halves).
4. Follow instructions [here](https://docs.moergo.com/go60-user-guide/customizing-key-layout/#putting-go60-into-bootloader-for-firmware-loading) to flash both sides of the Go60.

Works but open to some feedback/cleanup.
