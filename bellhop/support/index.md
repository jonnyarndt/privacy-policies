# Support for Bellhop: Time Awareness

Thanks for using Bellhop! Below you'll find answers to common questions and ways to get help.

---

## Frequently Asked Questions

**Where does Bellhop appear on my Mac?**
Bellhop lives entirely in the **menu bar** — there is no Dock icon. After launching, look for the bell icon in your menu bar. Clicking it opens a quick-controls popover where you can enable/disable the service, toggle audible and visual notifications, and open Settings.

**How do I enable or disable Bellhop?**
Click the Bellhop menu bar icon and use the **Enable Bellhop** toggle to turn the service on or off. You can also disable just the audible or visual features independently using the **Audible** and **Visual** toggles in the same popover.

**How do I change the notification interval?**
Click the menu bar icon, then select **Settings…**. In the **General** tab, find the **Time** section and use the **Interval** picker to choose **Hourly**, **30-Min**, or **15-Min**.

- **Hourly** — alerts fire at the top of every hour (:00)
- **30-Min** — alerts fire at :00 and :30
- **15-Min** — alerts fire at :00, :15, :30, and :45

**How do I change the notification sound?**
Click the menu bar icon, choose **Settings…**, and go to the **Sound** tab. You can pick from:

- **Grandfather Clock** — a synthesized Westminster chime with quarter-hour phrases and hourly bong strikes that match the current hour
- **Built-in** — 14 standard macOS system sounds (Basso, Blow, Bottle, Frog, Funk, Glass, Hero, Morse, Ping, Pop, Purr, Sosumi, Submarine, Tink)
- **Custom** — import your own WAV, MP3, M4A, or AIFF file using the **Browse** button

Clicking any sound in the list immediately plays a live preview.

**How do I change the visual notification?**
Open **Settings… → Visual** tab. Use the **Visual Mode** picker to choose:

- **Flash** — a full-screen white/black flash. Use **Flash Count** to set 1–5 flashes per alert.
- **Image (Bundled)** — displays one of 7 built-in graphics (abstract, clock, or nature themes).
- **Image (Custom)** — import your own PNG, JPEG, HEIC, TIFF, or BMP file.

For image modes, you can also adjust **Display Duration** (1–60 seconds), **Opacity** (0–100%), and toggle **Fade In / Out**.

**Will Bellhop interrupt me when I'm using Focus Mode or Do Not Disturb?**
By default, Bellhop fires regardless of your Focus Mode state. If you'd like it to stay silent while Focus Mode is active, open **Settings… → General**, find the **Service** section, and enable the **Respect Focus / DND** toggle.

**Which monitors does the visual notification appear on?**
Open **Settings… → General** and find the **Display** section. Set **Monitors** to either **Primary Monitor** or **All Monitors**.

**How do I quit Bellhop?**
Click the Bellhop menu bar icon and select **Quit Bellhop** at the bottom of the popover.

**How do I uninstall Bellhop?**
Drag Bellhop from your **Applications** folder to the Trash. To also remove all saved settings, run the following in Terminal:
```
defaults delete com.jonnyarndt.bellhop
```

**Does Bellhop collect any of my data?**
No. Bellhop does not collect, store, or transmit any personal data. See the full [Privacy Policy](https://jonnyarndt.github.io/products/bellhop/privacy-policy/) for details.

---

## Still Need Help?

If you're experiencing an issue not covered above or have a feature request, you're welcome to open a ticket on GitHub:

[Open an Issue on GitHub](https://github.com/jonnyarndt/products/issues/new)

Please include the product name (Bellhop), your macOS version, and a description of the problem or request.