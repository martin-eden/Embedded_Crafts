# What

My framework of embedded C++ libraries.

Each one has to be in separate repo to make installation possible
via `arduino-cli lib install`.

* ATmega328/P
  ![Dependency graph][Dependency graph]
  * Level 1
    * [me_BaseTypes][me_BaseTypes] (2024-02/2024-09)
  * Level 2
    * [me_BaseInterfaces][me_BaseInterfaces] (2025-08)
    * [me_Bits][me_Bits] (2024-10)
    * [me_ConvertUnits_Angle][me_ConvertUnits_Angle] (2024-05)
    * [me_Counters][me_Counters] (2024-12/2025-02)
    * [me_Eeprom][me_Eeprom] (2025-07)
    * [me_ProgramMemory][me_ProgramMemory] (2024-12)
    * [me_Timestamp][me_Timestamp] (2025-03)
    * [me_Uart][me_Uart] (2024-10/2024-12, 2025-07)
    * [me_WorkMemory][me_WorkMemory] (2024-12)
  * Level 3
    * [me_AddrsegTools][me_AddrsegTools] (2024, 2025)
    * [me_Bits_Workmem][me_Bits_Workmem] (2025-08)
    * [me_RunTime][me_RunTime] (2025-03)
    * [me_StoredCall][me_StoredCall] (2024-06)
    * [me_StreamsCollection][me_StreamsCollection] (2025-08)
    * [me_StreamTools][me_StreamTools] (2025-08)
  * Level 4
    * [me_CodecDecInt][me_CodecDecInt] (2024-10, 2024-12)
    * [me_Delays][me_Delays] (2025-08)
    * [me_ParseInteger][me_ParseInteger] (2024-05/2024-10)
    * [me_Pins][me_Pins] (2025-08)
    * [me_SerialTokenizer][me_SerialTokenizer] (2024-05/2024-06)
    * [me_WorkmemTools][me_WorkmemTools] (2024, 2025)
  * Level 5
    * [me_Console][me_Console] (2024-10)
    * [me_List][me_List] (2024-05/2024-06)
    * [me_ReadInteger][me_ReadInteger] (2024-10)
    * [me_Ws2812b][me_Ws2812b] (2024-03/2024-05) RGB stripe WS2812B: Driver
  * Level 6
    * [me_Menu][me_Menu] (2024-05/2024-06) Communication protocol framework
    * [me_Heap][me_Heap] (2024-10)
    * [me_RgbStripe][me_RgbStripe] (2024-09) RGB stripe WS2812B: Class for driver
  * Level 7
    * [me_RgbStripeConsole][me_RgbStripeConsole] (2024-09) RGB stripe WS2812B: Text interface for class

* ESP8266
  * [me_WifiShip][me_WifiShip] (2023-12/2024-02) WiFi: scan and connect

* Graveyard
  * [me_InstallStandardStreams][me_InstallStandardStreams] (2023-11/2024-05)
  * [me_UnoAddresses][me_UnoAddresses] (2024-05, 2024-12)
  * [me_SegmentProcessor][me_SegmentProcessor] (2024-12)
  * [me_MemsegStreams][me_MemsegStreams] (2025-08)
  * [me_Asciiz][me_Asciiz] (2024-12)

[Dependency graph]: https://raw.githubusercontent.com/martin-eden/Embedded_Crafts/master/Parts/My%20AVR%20framework.svg

[me_BaseTypes]: https://github.com/martin-eden/Embedded-me_BaseTypes

[me_BaseInterfaces]: https://github.com/martin-eden/Embedded-me_BaseInterfaces
[me_Bits]: https://github.com/martin-eden/Embedded-me_Bits
[me_ConvertUnits_Angle]: https://github.com/martin-eden/Embedded-me_ConvertUnits_Angle
[me_Counters]: https://github.com/martin-eden/Embedded-me_Counters
[me_Eeprom]: https://github.com/martin-eden/Embedded-me_Eeprom
[me_ProgramMemory]: https://github.com/martin-eden/Embedded-me_ProgramMemory
[me_Timestamp]: https://github.com/martin-eden/Embedded-me_Timestamp
[me_Uart]: https://github.com/martin-eden/Embedded-me_Uart
[me_WorkMemory]: https://github.com/martin-eden/Embedded-me_WorkMemory

[me_AddrsegTools]: https://github.com/martin-eden/Embedded-me_AddrsegTools
[me_Bits_Workmem]: https://github.com/martin-eden/Embedded-me_Bits_Workmem
[me_RunTime]: https://github.com/martin-eden/Embedded-me_RunTime
[me_StoredCall]: https://github.com/martin-eden/Embedded-me_StoredCall
[me_StreamsCollection]: https://github.com/martin-eden/Embedded-me_StreamsCollection
[me_StreamTools]: https://github.com/martin-eden/Embedded-me_StreamTools

[me_CodecDecInt]: https://github.com/martin-eden/Embedded-me_CodecDecInt
[me_Delays]: https://github.com/martin-eden/Embedded-me_Delays
[me_ParseInteger]: https://github.com/martin-eden/Embedded-me_ParseInteger
[me_Pins]: https://github.com/martin-eden/Embedded-me_Pins
[me_SerialTokenizer]: https://github.com/martin-eden/Embedded-me_SerialTokenizer
[me_WorkmemTools]: https://github.com/martin-eden/Embedded-me_WorkmemTools

[me_Console]: https://github.com/martin-eden/Embedded-me_Console
[me_List]: https://github.com/martin-eden/Embedded-me_List
[me_ReadInteger]: https://github.com/martin-eden/Embedded-me_ReadInteger
[me_Ws2812b]: https://github.com/martin-eden/Embedded-me_Ws2812b

[me_Heap]: https://github.com/martin-eden/Embedded-me_Heap
[me_Menu]: https://github.com/martin-eden/Embedded-me_Menu
[me_RgbStripe]: https://github.com/martin-eden/Embedded-me_RgbStripe

[me_RgbStripeConsole]: https://github.com/martin-eden/Embedded-me_RgbStripeConsole

[me_WifiShip]: https://github.com/martin-eden/Embedded-me_WifiShip

[me_InstallStandardStreams]: https://github.com/martin-eden/Embedded-me_InstallStandardStreams
[me_UnoAddresses]: https://github.com/martin-eden/Embedded-me_UnoAddresses
[me_SegmentProcessor]: https://github.com/martin-eden/Embedded-me_SegmentProcessor
[me_MemsegStreams]: https://github.com/martin-eden/Embedded-me_MemsegStreams
[me_Asciiz]: https://github.com/martin-eden/Embedded-me_Asciiz
