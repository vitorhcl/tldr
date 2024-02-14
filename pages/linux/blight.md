# blight

> Change and show the display brightness.
> More information: <https://github.com/gutjuri/blight>.

- Set display brightness to a specific percentage (using [r]elative units):

`blight set {{1..100}} -r`

- Show current display brightness:

`blight show`

- Show maximum display brightness:

`blight max`

- Increase display brightness in % (using [r]elative units):

`blight inc {{number}} -r`

- Decrease display brightness with internal units:

`blight dec {{number}}`

- Specify the [f]ile containing the current brightness (defaults to `/sys/class/backlight/intel_backlight/brightness`):

`blight -f {{path/to/current_brightness}}`

- Specify the file containing the [m]ax brightness (defaults to `/sys/class/backlight/intel_backlight/max_brightness`):

`blight -m {{path/to/max_brightness}}`
