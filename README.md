![example](https://ric0x101010.github.io/xivmicroparser/img/example.png)

# xivmicropaser
XIV Micro Parser for Overlay Plugin.

It serves as a simplified presentation of the most important information about the fight.
Broken down to:
- The actual Fight Time.
- The Time to Kill (TTK). **Is calculated on the basis of the current rDPS and can be different, but is only intended as a guideline.** 
- The life points of the enemy.
- The group rDPS.

### Test Feature
- Checkbox for 50% TTK, this is there to get the time to kill for the 50% limit in fights like P8S P1. The percentage is also calculated with half of the HP so that 0% is displayed at 50% HP.

## Usage

### Quick setup

No download needed.
Use this as overlay URL:

> `ric0x101010.github.io/xivmicroparser/`

### Detailed

1. Open ACT.
2. Plugins > OverlayPlugin.dll > Add 'Mini Parse' with any name (e.g. Totoro).
3. Read warning below.
4. Go to the new tab (e.g. Totoro), and set url as above.
