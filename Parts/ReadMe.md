# What

My relatively recent Embedded C++ libraries.

Each one has to be in separate repo to make installation possible
via `arduino-cli lib install`.

* Boring (improving quality of life)
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
  * Communication protocol framework
    * [me_Menu][me_Menu]
  * External devices
    * [me_Ws2812b][me_Ws2812b]
  * API wrappers
    * [me_WifiShip][me_WifiShip]

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
[me_WifiShip]: https://github.com/martin-eden/Embedded-me_WifiShip
