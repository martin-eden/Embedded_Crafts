# What

My embedded C++ libraries.

Each one has to be in separate repo to make installation possible
via `arduino-cli lib install`.

* Boring (ground quality of life)
  * Bootstrap
    * [me_BaseTypes][me_BaseTypes]
    * [me_UartSpeeds][me_UartSpeeds]
    * [me_InstallStandardStreams][me_InstallStandardStreams]
  * Memory
    * [me_MemoryPoint][me_MemoryPoint]
    * [me_UnoAddresses][me_UnoAddresses]
    * [me_MemorySegment][me_MemorySegment]
    * [me_ManagedMemory][me_ManagedMemory]
  * Data structures
    * [me_StoredCall][me_StoredCall]
    * [me_List][me_List]
  * Parsing
    * [me_SerialTokenizer][me_SerialTokenizer]
    * [me_ParseInteger][me_ParseInteger]
  * Unit conversion
    * [me_ConvertUnits_Angle][me_ConvertUnits_Angle]

* Less boring
  * [me_Menu][me_Menu] Communication protocol framework
  * [me_Ws2812b][me_Ws2812b] RGB stripe (WS2112B) driver
  * [me_RgbStripe][me_RgbStripe] Class for RGB stripe
  * [me_RgbStripeConsole][me_RgbStripeConsole] (2024-09) Text interface for RGB stripe
  * [me_WifiShip][me_WifiShip] Esplora WiFi scanning and connection

[me_BaseTypes]: https://github.com/martin-eden/Embedded-me_BaseTypes
[me_UartSpeeds]: https://github.com/martin-eden/Embedded-me_UartSpeeds
[me_InstallStandardStreams]: https://github.com/martin-eden/Embedded-me_InstallStandardStreams

[me_MemoryPoint]: https://github.com/martin-eden/Embedded-me_MemoryPoint
[me_UnoAddresses]: https://github.com/martin-eden/Embedded-me_UnoAddresses
[me_MemorySegment]: https://github.com/martin-eden/Embedded-me_MemorySegment
[me_ManagedMemory]: https://github.com/martin-eden/Embedded-me_ManagedMemory

[me_StoredCall]: https://github.com/martin-eden/Embedded-me_StoredCall
[me_List]: https://github.com/martin-eden/Embedded-me_List

[me_SerialTokenizer]: https://github.com/martin-eden/Embedded-me_SerialTokenizer
[me_ParseInteger]: https://github.com/martin-eden/Embedded-me_ParseInteger

[me_ConvertUnits_Angle]: https://github.com/martin-eden/Embedded-me_ConvertUnits_Angle

[me_Menu]: https://github.com/martin-eden/Embedded-me_Menu
[me_Ws2812b]: https://github.com/martin-eden/Embedded-me_Ws2812b
[me_RgbStripe]: https://github.com/martin-eden/Embedded-me_RgbStripe
[me_RgbStripeConsole]: https://github.com/martin-eden/Embedded-me_RgbStripeConsole
[me_WifiShip]: https://github.com/martin-eden/Embedded-me_WifiShip
