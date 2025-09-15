# What

My framework of embedded C++ libraries.

Each one has to be in separate repo to make installation possible
via `arduino-cli lib install`.

* ATmega328/P
  ![Dependency graph][Dependency graph]
  * Level 1
    * [me_BaseTypes][me_BaseTypes] (2024)
  * Level 2
    * [me_AddrsegTools][me_AddrsegTools] (2024)
    * [me_Bits][me_Bits] (2024)
    * [me_ConvertUnits_Angle][me_ConvertUnits_Angle] (2024)
    * [me_Counters][me_Counters] (2024)
    * [me_Timestamp][me_Timestamp] (2025)
    * [me_WorkMemory][me_WorkMemory] (2024)
  * Level 3
    * [me_BaseInterfaces][me_BaseInterfaces] (2025)
    * [me_Bits_Workmem][me_Bits_Workmem] (2025)
    * [me_RunTime][me_RunTime] (2025)
  * Level 4
    * [me_Delays][me_Delays] (2025)
    * [me_Eeprom][me_Eeprom] (2025)
    * [me_Pins][me_Pins] (2025)
    * [me_ProgramMemory][me_ProgramMemory] (2024)
    * [me_StoredCall][me_StoredCall] (2024)
    * [me_StreamTools][me_StreamTools] (2025)
    * [me_Uart][me_Uart] (2024)
    * [me_WriteInteger][me_WriteInteger] (2024)
  * Level 5
    * [me_StreamsCollection][me_StreamsCollection] (2025)
    * [me_Ws2812b][me_Ws2812b] (2024) RGB stripe WS2812B: Driver
  * Level 6
    * [me_StreamTokenizer][me_StreamTokenizer] (2025)
    * [me_WorkmemTools][me_WorkmemTools] (2024)
  * Level 7
    * [me_List][me_List] (2024)
    * [me_ReadInteger][me_ReadInteger] (2024)
    * [me_RgbStripe][me_RgbStripe] (2024) RGB stripe WS2812B: Class for driver
  * Level 8
    * [me_Console][me_Console] (2024)
  * Level 9
    * [me_Heap][me_Heap] (2024)
    * [me_Menu][me_Menu] (2024) Communication protocol framework
    * [me_RgbStripeConsole][me_RgbStripeConsole] (2024) RGB stripe WS2812B: Text interface for class

* ESP8266
  * [me_WifiShip][me_WifiShip] (2023) WiFi: scan and connect

* Graveyard
  * [me_InstallStandardStreams][me_InstallStandardStreams] (2023)
  * [me_UnoAddresses][me_UnoAddresses] (2024)
  * [me_SegmentProcessor][me_SegmentProcessor] (2024)
  * [me_MemsegStreams][me_MemsegStreams] (2025)
  * [me_Asciiz][me_Asciiz] (2024)
  * [me_SerialTokenizer][me_SerialTokenizer] (2024)
  * [me_ParseInteger][me_ParseInteger] (2024)

[Dependency graph]: https://raw.githubusercontent.com/martin-eden/Embedded_Crafts/master/Parts/My%20AVR%20framework.svg

[me_BaseTypes]: https://github.com/martin-eden/Embedded-me_BaseTypes

[me_AddrsegTools]: https://github.com/martin-eden/Embedded-me_AddrsegTools
[me_Bits]: https://github.com/martin-eden/Embedded-me_Bits
[me_ConvertUnits_Angle]: https://github.com/martin-eden/Embedded-me_ConvertUnits_Angle
[me_Counters]: https://github.com/martin-eden/Embedded-me_Counters
[me_Timestamp]: https://github.com/martin-eden/Embedded-me_Timestamp
[me_WorkMemory]: https://github.com/martin-eden/Embedded-me_WorkMemory

[me_BaseInterfaces]: https://github.com/martin-eden/Embedded-me_BaseInterfaces
[me_Bits_Workmem]: https://github.com/martin-eden/Embedded-me_Bits_Workmem
[me_RunTime]: https://github.com/martin-eden/Embedded-me_RunTime

[me_Delays]: https://github.com/martin-eden/Embedded-me_Delays
[me_Eeprom]: https://github.com/martin-eden/Embedded-me_Eeprom
[me_Pins]: https://github.com/martin-eden/Embedded-me_Pins
[me_ProgramMemory]: https://github.com/martin-eden/Embedded-me_ProgramMemory
[me_StoredCall]: https://github.com/martin-eden/Embedded-me_StoredCall
[me_StreamTools]: https://github.com/martin-eden/Embedded-me_StreamTools
[me_Uart]: https://github.com/martin-eden/Embedded-me_Uart

[me_StreamsCollection]: https://github.com/martin-eden/Embedded-me_StreamsCollection
[me_Ws2812b]: https://github.com/martin-eden/Embedded-me_Ws2812b

[me_StreamTokenizer]: https://github.com/martin-eden/Embedded-me_StreamTokenizer
[me_WorkmemTools]: https://github.com/martin-eden/Embedded-me_WorkmemTools
[me_WriteInteger]: https://github.com/martin-eden/Embedded-me_WriteInteger

[me_List]: https://github.com/martin-eden/Embedded-me_List
[me_ReadInteger]: https://github.com/martin-eden/Embedded-me_ReadInteger
[me_RgbStripe]: https://github.com/martin-eden/Embedded-me_RgbStripe

[me_Console]: https://github.com/martin-eden/Embedded-me_Console

[me_Heap]: https://github.com/martin-eden/Embedded-me_Heap
[me_Menu]: https://github.com/martin-eden/Embedded-me_Menu
[me_RgbStripeConsole]: https://github.com/martin-eden/Embedded-me_RgbStripeConsole

[me_WifiShip]: https://github.com/martin-eden/Embedded-me_WifiShip

[me_DebugPrints]: https://github.com/martin-eden/Embedded-me_DebugPrints
[me_DigitalSignalRecorder]: https://github.com/martin-eden/Embedded-me_DigitalSignalRecorder
[me_FrequencyGenerator]: https://github.com/martin-eden/Embedded-me_FrequencyGenerator
[me_ModulatedSignalPlayer]: https://github.com/martin-eden/Embedded-me_ModulatedSignalPlayer

[me_InstallStandardStreams]: https://github.com/martin-eden/Embedded-me_InstallStandardStreams
[me_UnoAddresses]: https://github.com/martin-eden/Embedded-me_UnoAddresses
[me_SegmentProcessor]: https://github.com/martin-eden/Embedded-me_SegmentProcessor
[me_MemsegStreams]: https://github.com/martin-eden/Embedded-me_MemsegStreams
[me_Asciiz]: https://github.com/martin-eden/Embedded-me_Asciiz
[me_SerialTokenizer]: https://github.com/martin-eden/Embedded-me_SerialTokenizer
[me_ParseInteger]: https://github.com/martin-eden/Embedded-me_ParseInteger
