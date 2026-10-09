

Uploading Feature Demo.mp4…

![Uploading TH5280网络收音机的英文翻译 (1).png…]()
![Uploading TH5280网络收音机的英文翻译 (3).png…]()

HT5280 Multifunctional Internet Radio / FM Radio / Aviation Radio
Supports firmware upgrade, with open-source firmware (not source code), which enables subsequent maintenance of system stability and continuous optimization and updates
FM, LW, MW, SW, OIRT, AIR, internet radio, clock & weather, clock perpetual calendar (with power-off memory), USB audio playback, computer sound card function, software custom setting function, compatible with computer-configured internet radio
It supports multi-language settings and Chinese/English voice broadcast function, and the voice prompt can be turned off in the system settings.
Supports custom LOGO upload; to modify the boot screen via computer software, a resolution of 320X240 pixels is required
It supports storing 3 sets of WiFi names and passwords, which facilitates the mobile playback of internet radio, for example, at home, in the office, or via mobile hotspot; when connecting to the 4th WiFi, the first stored WiFi name will be overwritten.
Voice Broadcast
1. Provide user-friendly operation prompts for people with poor eyesight
2. Enhance entertainment value and playability
3. Supports Chinese and English voice announcements; customization is available for other languages as needed.
4. Enabling the voice broadcast will slow down the operation and result in a poor user experience. You can turn off the voice prompt in (System Settings), and it is disabled by default.
NXP TEF6686 Radio Chip
The radio program list can display 500 radio stations
Receiver sensitivity: -92dBm to -96dBm
HT5280 Internet Radio

It supports storing 3 sets of WiFi names and passwords, which facilitates the mobile playback of internet radio, for example, at home, in the office, or via mobile hotspot; when connecting to the 4th WiFi, the first stored WiFi name will be overwritten.
   -- Upload and add online radio stations using mobile and computer software
    -- Auxiliary software (capable of playback) can be used to play online radio stations that this radio set cannot play natively, by bridging them to the radio via a computer
2. Streaming Media Playback Capability
- Protocol: Supports HTTP / HTTPS internet radio Streaming Media streams
- Playback controls: Previous track, Next track, Pause/Play, Menu settings
- Background Playback: When background playback is enabled, the online radio can keep playing audio without interruption even if you return to the home page or switch to other function interfaces
- Visualization: Playback Page Spectrum Display, allowing intuitive viewing of the dynamic audio spectrum effects
- Sound Effect: Built-in sound effect equalizer adjustment for customizable audio experience
- Volume: Unified adjustment of volume from level 0 to 30, which is consistent with the overall volume system of the device
- 3. Radio Station Library Management
- My Favorites: Long-press the encoder on the playback page to add/remove a radio station to/from favorites, for quick access to your preferred stations
- Recently Played: Automatically records your listening history for quick replay
- Radio Management: Long press to delete unwanted radio entries is now supported for the full radio station list
- Number of radio stations: 1500 can be stored, and the capacity can be expanded without adding other functions later
- Bulk import: via the PC configuration tool to connect to a computer via USB for bulk import of radio station addresses (recommended); manual entry of radio stations via mobile web page is also supported (subject to firmware availability)
- 3. WiFi Network Capability (Foundation of Internet Radio)

1. WiFi Switch: The wireless network can be manually enabled or disabled in the system settings.
2. Multi-WiFi memory, supporting up to 3 sets of saved WiFi configurations; when a 4th WiFi set is added, the system will automatically replace the oldest recorded entry; upon startup, the device will automatically prioritize connecting to the available WiFi with the strongest signal strength
3. Two distribution network modes
  - Phone Network Configuration: The device generates a hotspot HT5280‑NetRadio, the phone connects to the hotspot, opens the network configuration page, and enters the WiFi name and password to complete the network configuration
  - PC Tool Network Configuration: Connect the device to a computer via USB, and the PC configuration tool directly writes the WiFi account and password, which is suitable for batch setup
4. Locale: CN/EU/US/AUTO is selectable to adapt to time zones and network DNS of different regions, which affects Internet radio, weather and NTP time synchronization
Smart Clock & Weather System
• Supports NTP network automatic time synchronization, perpetual calendar, and 12/24-hour time formats
• Built-in clock chip, which keeps accurate time automatically after the time is set via WiFi or manually, with power-off memory function.
• Obtain weather information via the internet: 9-digit city codes can be filled in for domestic locations, while English place names or latitude/longitude settings are supported for overseas regions, and meteorological data including temperature, humidity, wind force, etc. will be displayed
• Timer Power On/Off: Supports daily scheduled automatic power on/off; for scheduled power on, you can choose to directly play FM or online radio after wake-up
• 3P external control H-pin level linkage: The device outputs a high level when running and a low level when in sleep/shutdown state, which can be connected externally to link with peripheral devices.
Human-Computer Interaction and Display
• Color TFT landscape screen with 320×240 resolution, simple 8-grid home page UI; supports multiple display themes, screen brightness adjustment, and screensaver sleep function
• Rotary encoder + power standby key combined operation: rotate for selection, short press for confirmation, long press for context menu; supports encoder lock to prevent accidental touch, double-click to unlock
• Volume is adjustable in 0‑30 levels; equipped with a headphone jack, which automatically detects headphone insertion and switches audio output: the left port is for stereo audio output to an amplifier, while the right port is for headphone driving (do not connect an amplifier to this port, as it will cause distortion)
3P External Control Interface (Featured Expansion Capability)
On-board 3P pin header interface: H (operating level), M (FM squelch level), GND (ground)
- Pin H: Timed power on/off linkage, outputs high when powered on and running, outputs low when in sleep shutdown mode; application scenarios (control the power supply of the power amplifier to turn on synchronously with the timer, or control other devices)
- M pin: When the radio detects a valid station, it outputs a high level; when there is no signal on an empty frequency, it outputs a low level. Application scenario (there is no noise during monitoring, only the signal sound from the radio station; a device such as a power supply can be turned on when a signal is present)
Note: This is a logic level signal; an additional driving isolation circuit (such as an optocoupler) is required to drive relays and high-power peripherals.
Brief Specification Summary
• Main controller: ESP32 S3
• PCB circuit board: 1.2mm 4-layer circuit board, designed in accordance with RF standards to enhance receiving sensitivity and deliver stronger anti-interference capability
• Radio chip: TEF6686 multi-band radio with high sensitivity
• Screen: 2.8-inch TFT landscape color LCD, 320×240 resolution, non-touch
• Power supply: built-in lithium battery, USB charging
• Time-division multiplexing of USB port: charging / USB flash drive playback / PC sound card / PC configuration
• Audio: Volume levels 0‑30, headphone detection
• Storage: WiFi can remember up to 3 groups; the maximum number of stations in the radio station list is approximately 5000
• Host computer editing software
• Internet radio auxiliary software
<img width="4096" height="3072" alt="数据测试" src="https://github.com/user-attachments/assets/915fdad2-e5aa-460e-a58a-bc007b0ffa3b" />


