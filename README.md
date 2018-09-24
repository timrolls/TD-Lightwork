# TD-Lightwork

A network that uses CSV or SOP coordinates to map screen content onto LEDs.
Includes a 3d-capable previsualizer.

To quickly generate CSV maps of your existing layouts using computer vision, check out Lightwork: https://github.com/PWRFLcreative/Lightwork

## Installation

### For Fadecandy output:
The modified opc.py included in this repo, goes to: \Derivative\TouchDesigner088\bin\Lib

Run the included windows fcserver to send to fadecandy devices
The included conf.json is set up for 60 pixel strips.

### For DMX/Artnet/sACN
Just configure the DMX OUT Chop for your output device/network

## Credits

Based on fadecandy work from these repos:

https://github.com/Swaeg/TouchCandy

https://github.com/Heljick/FCDesigner
