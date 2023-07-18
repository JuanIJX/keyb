# KeyB

Console commands

## Installation

Use the package manager npm to install KeyB.

```bash
npm install @ijx/keyb
```

## Usage

```js
import KeyB from "@ijx/keyb"

// Event called to close error
KeyB.onExitError(error => {});

// Event called in bucle
KeyB.onError(error => {});

// Event called in stop
KeyB.onClose(async () => {});

// Command controller
KeyB.bucle(async (cadena, cmdName, args) => {
	// Code here
});

// For stop console
KeyB.stop();
```