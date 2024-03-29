
![example 1.0](https://ric0x101010.github.io/xivmicroparser/img/example_1.0.png)

# xivmicropaser
XIV Micro Parser for Overlay Plugin.

It serves as a simplified presentation of the most important information about the fight.
Broken down to:
- The actual Fight Time.
- The Time to Kill (TTK). **Is calculated on the basis of the current rDPS and can be different, but is only intended as a guideline.** 
- Kill Time (KT), calculated on Time in Fight and Time to Kill
- Progress Bar
- The group DPS.

### Test Feature
- Checkbox for 50% TTK, this is there to get the time to kill for the 50% limit in fights like P8S P1. The percentage is also calculated with half of the HP so that 0% is displayed at 50% HP.

## Usage

### Quick setup

No download needed.
Use this as overlay URL:

> `ric0x101010.github.io/xivmicroparser/`

### Detailed

1. Open ACT.
2. Plugins > OverlayPlugin.dll > Add 'Mini Parse' with any name (e.g. XIVmicropaser).
3. Read warning below.
4. Go to the new tab (e.g. XIVmicropaser), and set url as above.

You can use it with IINact, so add this to your Browsingway/BunnyHUD
> `https://ric0x101010.github.io/xivmicroparser/?OVERLAY_WS=ws://127.0.0.1:10501/ws`
