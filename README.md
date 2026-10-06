# Temperature Trainer

A small web game for learning Celsius ↔ Fahrenheit conversions well enough to estimate them by memory.

## Play

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server
```

No build step or dependencies.

## Features

- Formula and a mental shortcut shown at the top for the current direction
- Switch between °C → °F and °F → °C
- Random temperatures; type your answer and press Enter (Enter again for the next one)
- Feedback shows how many degrees off you were, the exact answer, and whether you were too high or too low
- Stats per direction: answered, average error, % within 3°, current streak, and a bar strip of recent errors
- Stats are saved in the browser's local storage; use "Reset stats" to clear them

## Ideas

- Weather graphics that change with the temperature (snow, sun, etc.)
