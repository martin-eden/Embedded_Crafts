# What

My embedded C++ libraries.

Each one has to be in separate repo to make installation possible
via `arduino-cli lib install`.

* Boring (ground quality of life)
  * Bootstrap
    * [me_BaseTypes][me_BaseTypes] (2024-02, 2024-05)
    * [me_UartSpeeds][me_UartSpeeds] (2024-03)
    * [me_InstallStandardStreams][me_InstallStandardStreams] (2023-11, 2024-05)
  * Memory
    * [me_MemoryPoint][me_MemoryPoint] (2024-05)
    * [me_UnoAddresses][me_UnoAddresses] (2024-05)
    * [me_MemorySegment][me_MemorySegment] (2024-05 .. 2024-06)
    * [me_ManagedMemory][me_ManagedMemory] (2024-06)
  * Data structures
    * [me_StoredCall][me_StoredCall] (2024-06)
    * [me_List][me_List] (2024-05 .. 2024-06)
  * Parsing
    * [me_SerialTokenizer][me_SerialTokenizer] (2024-05 .. 2024-06)
    * [me_ParseInteger][me_ParseInteger] (2024-05)
  * Unit conversion
    * [me_ConvertUnits_Angle][me_ConvertUnits_Angle] (2024-05)

* Less boring
  * [me_WifiShip][me_WifiShip] (2023-12 .. 2024-02) Esplora WiFi scanning and connection
  * [me_Ws2812b][me_Ws2812b] (2024-03 .. 2024-05) RGB stripe (WS2112B) driver
  * [me_Menu][me_Menu] (2024-05 .. 2024-06) Communication protocol framework
  * [me_RgbStripe][me_RgbStripe] (2024-09) Class for RGB stripe
  * [me_RgbStripeConsole][me_RgbStripeConsole] (2024-09) Text interface for RGB stripe

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
