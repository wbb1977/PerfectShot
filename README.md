# PerfectShot
Vanialla World of Warcraft Screenshot Addon

# Function
Hides UI during the screenshot.

# How to use?
Go to the key binding dialog and bind three new keys:

* 'Screenshot with names' - Hide UI and show names on screenshot.
* 'Screenshot without names - Hide UI and hide names on screenshot.
* 'Screenshot without names / target name' - Hide UI and hide names and target name on screenshot.

# Chat command
To do a series of screenshots automatically:

* /ps <number screenshots> <delay in seconds> [<show names: 1>]

Takes X screenshots, after each screenshot the addon waits Y seconds. To show names append a '1' otherwise names are not shown (default) on screenshot.

You can cancel a series anytime via '/ps cancel'. Also if you program an new series it overrides any active series.

Examples
* '/ps 10 3' - Makes 10 screenshot, 3 seconds pause between each shot. Names off.
* '/ps 10 3 1' - Same, but names on.
* '/ps 10000 300' - Makes every 5 minutes one shot as long as you play :) 

