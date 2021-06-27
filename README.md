# Tiny Motion Trainer for APDS

The original codes are on https://github.com/googlecreativelab/tiny-motion-trainer .

This repo contains Tiny Motion Trainer for APDS based on the original codes.

You need to run [TF4Micro Motion Kit for APDS](https://github.com/kuromusha/tf4micro-motion-kit-apds) on Arduino Nano 33 BLE Sense to use this tool.

---

## How to run on local environment

This tool can be run on your local environment:

```
$ cd frontend
$ npm install
$ npm run-script dev
```

---

## What are changed from the original codes

- Proximity  
Proximity is also used to start/stop captures.
- Gesture (4 ways; up, down, left and right)
- RGB Color  
RGB Color is converted into HSV Color.

The code diffs are [here](https://github.com/kuromusha/tiny-motion-trainer-apds/compare/6586e6249eea48a466ada46c42f5cc2fa73bf6a4..master).
