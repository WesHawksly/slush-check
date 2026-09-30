# Slush Check

Build a drink mix and find out whether it will turn to slush in a Ninja SLUSHi before you pour it in.

**Open the app:** https://weshawksly.github.io/slush-check/

<img src="qr-code.png" alt="QR code linking to the Slush Check app" width="220">

Scan the code with your phone's camera to open the app.

## Install on your phone

Once installed, it gets its own icon, opens full screen, and works offline.

**Android**

1. Open the link above in Chrome or Samsung Internet.
2. Tap **⋮** and choose **Install app** or **Add to home screen**.

**iPhone**

1. Open the link above in Safari.
2. Tap the **Share** button (the square with an arrow pointing up).
3. Scroll down and tap **Add to Home Screen**, then **Add**.

On iPhone, use the app from its home screen icon. Safari clears a website's saved data after about a week without a visit, so mixes saved in the browser can disappear. Mixes saved in the home screen app stay put. The two also keep separate lists, so mixes saved in Safari won't appear in the home screen app.

## What it does

- Pick ingredients from a built-in list of about 90 drinks, syrups, milks, spirits and mixers, and enter the amounts in oz, ml, cups, tbsp, tsp or grams.
- Choose the brand you're using, or add a new one by scanning its nutrition label with your camera.
- See whether the mix will slush, which preset to use (Slush, Spiked Slush, Frozen Juice, Milkshake or Frappé), and how far to adjust the frozen level.
- Get specific fixes when a mix won't work, such as how much simple syrup to add, with one-tap buttons for some of them.
- Save your favorite mixes on your phone.

## How the check works

Sugar and alcohol lower a drink's freezing point. That keeps the ice crystals small, so the machine can churn them into slush. The app adds up the sugar and alcohol in each ingredient and compares the mix with Ninja's guidance:

| | Limit |
|---|---|
| Sugar | at least 4% (6–16% gives the best texture) |
| Alcohol for Spiked Slush | 2.8–16% ABV |
| Fill lines | 16–64 oz (you can change these in the app) |

Sugar % is grams of sugar per 100 ml. For a finished slush mix that is very close to the Brix reading you'd get from a refractometer.

Results are estimates. Check your SLUSHi manual for the rules that apply to your model.

## Updating the app

The app's version number is shown at the bottom of the screen. When shipping a change, bump `APP_VERSION` in `index.html` and `VERSION` in `sw.js`, then upload both files. Installed copies pick up the update the next time they open while online.
