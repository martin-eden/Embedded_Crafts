# What

My framework of embedded C++ libraries.

Each one has to be in separate repo to make installation possible
via `arduino-cli lib install`.

* Boring (ground quality of life)
  * Bootstrap
    * [me_BaseTypes][me_BaseTypes] (2024-02/2024-09)
    * [me_InstallStandardStreams][me_InstallStandardStreams] (2023-11/2024-05)
    * [me_Uart][me_Uart] (2024-10/2024-12, 2025-07)
    * [me_Counters][me_Counters] (2024-12/2025-02)
      * [me_RunTime][me_RunTime] (2025-03)
    * [me_Pins][me_Pins] (2025-08)
  * Memory
    * [me_UnoAddresses][me_UnoAddresses] (2024-05, 2024-12)
    * [me_MemorySegment][me_MemorySegment] (2024-05/2024-10)
    * [me_ManagedMemory][me_ManagedMemory] (2024-06/2024-10)
    * [me_SegmentProcessor][me_SegmentProcessor] (2024-12)
    * [me_Heap][me_Heap] (2024-10)
    * [me_WorkMemory][me_WorkMemory] (2024-12)
    * [me_ProgramMemory][me_ProgramMemory] (2024-12)
    * [me_Eeprom][me_Eeprom] (2025-07)
  * Output
    * [me_Console][me_Console] (2024-10)
  * Base types parsing/compiling
    * [me_SerialTokenizer][me_SerialTokenizer] (2024-05/2024-06)
    * [me_ParseInteger][me_ParseInteger] (2024-05/2024-10)
    * [me_ReadInteger][me_ReadInteger] (2024-10)
    * [me_CodecDecInt][me_CodecDecInt] (2024-10, 2024-12)
    * [me_Bits][me_Bits] (2024-10)
    * [me_Bits_Workmem][me_Bits_Workmem] (2025-08)
    * [me_Asciiz][me_Asciiz] (2024-12)
  * Units conversion
    * [me_ConvertUnits_Angle][me_ConvertUnits_Angle] (2024-05)
    * [me_Timestamp][me_Timestamp] (2025-03)
  * Data structures
    * [me_List][me_List] (2024-05/2024-06)
    * [me_StoredCall][me_StoredCall] (2024-06)

* Less boring
  * Esplora WiFi
    * [me_WifiShip][me_WifiShip] (2023-12/2024-02) WiFi: scan and connect
  * Communication protocol framework
    * [me_Menu][me_Menu] (2024-05/2024-06)
  * RGB stripe WS2812B
    * [me_Ws2812b][me_Ws2812b] (2024-03/2024-05) Driver
    * [me_RgbStripe][me_RgbStripe] (2024-09) Class for driver
    * [me_RgbStripeConsole][me_RgbStripeConsole] (2024-09) Text interface for class

[me_BaseTypes]: https://github.com/martin-eden/Embedded-me_BaseTypes
[me_InstallStandardStreams]: https://github.com/martin-eden/Embedded-me_InstallStandardStreams
[me_Uart]: https://github.com/martin-eden/Embedded-me_Uart
[me_Counters]: https://github.com/martin-eden/Embedded-me_Counters
[me_RunTime]: https://github.com/martin-eden/Embedded-me_RunTime
[me_Pins]: https://github.com/martin-eden/Embedded-me_Pins

[me_UnoAddresses]: https://github.com/martin-eden/Embedded-me_UnoAddresses
[me_MemorySegment]: https://github.com/martin-eden/Embedded-me_MemorySegment
[me_ManagedMemory]: https://github.com/martin-eden/Embedded-me_ManagedMemory
[me_SegmentProcessor]: https://github.com/martin-eden/Embedded-me_SegmentProcessor
[me_Heap]: https://github.com/martin-eden/Embedded-me_Heap
[me_WorkMemory]: https://github.com/martin-eden/Embedded-me_WorkMemory
[me_ProgramMemory]: https://github.com/martin-eden/Embedded-me_ProgramMemory
[me_Eeprom]: https://github.com/martin-eden/Embedded-me_Eeprom

[me_Console]: https://github.com/martin-eden/Embedded-me_Console

[me_SerialTokenizer]: https://github.com/martin-eden/Embedded-me_SerialTokenizer
[me_ParseInteger]: https://github.com/martin-eden/Embedded-me_ParseInteger
[me_ReadInteger]: https://github.com/martin-eden/Embedded-me_ReadInteger
[me_CodecDecInt]: https://github.com/martin-eden/Embedded-me_CodecDecInt
[me_Bits]: https://github.com/martin-eden/Embedded-me_Bits
[me_Bits_Workmem]: https://github.com/martin-eden/Embedded-me_Bits_Workmem
[me_Asciiz]: https://github.com/martin-eden/Embedded-me_Asciiz

[me_ConvertUnits_Angle]: https://github.com/martin-eden/Embedded-me_ConvertUnits_Angle
[me_Timestamp]: https://github.com/martin-eden/Embedded-me_Timestamp

[me_StoredCall]: https://github.com/martin-eden/Embedded-me_StoredCall
[me_List]: https://github.com/martin-eden/Embedded-me_List

[me_Menu]: https://github.com/martin-eden/Embedded-me_Menu
[me_Ws2812b]: https://github.com/martin-eden/Embedded-me_Ws2812b
[me_RgbStripe]: https://github.com/martin-eden/Embedded-me_RgbStripe
[me_RgbStripeConsole]: https://github.com/martin-eden/Embedded-me_RgbStripeConsole
[me_WifiShip]: https://github.com/martin-eden/Embedded-me_WifiShip
