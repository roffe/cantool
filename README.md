### cantool

CLI tool for CAN monitoring and ECU flashing and also home for toy code like talking to SAAB ECM's such as CIM and SID

#### Example

```go
go run .\cmd\cantool\main.go -p com3 -b 2000000 -a CANusb -c t5 -t t5 info
uploading bootloader 100% [====================] (1.793 kB/s) took: 1.029s
------------------------------
This is a Trionic 5.5 ECU with 256 kB of FLASH
----- ECU info ---------------
Part Number:  4780656
Software ID:  4782934
SW Version:   A554X24L.18C
Engine Type:  B204LM 900    ROFFE ST2
IMMO Code:    ******
Other Info:   LX1
ROM Start:    0x040000
Code End:     0x076D39
ROM End:      0x07FFFF
------------------------------
Resetting ECU
```

