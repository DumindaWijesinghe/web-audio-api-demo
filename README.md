# web-audio-api-demo
To see how powerful the Web Audio API is, I tried to build a synthesizer that runs in the browser and managed to build the following functionality into the "synth". 

1. Three oscillators.
2. Pitch controls for each oscillator.
3. Three-channel mixer.
4. Reverb effect on the master channel.
5. Keyboard to play C major scale (so we won't sound awful).
6. Release envelop for key release.
7. Oscilloscope (so we can see the actual waveshape).

![Imgur](https://i.imgur.com/zo5mQaI.gif)

We can use [Web Audio Inspector](https://github.com/google/audion/wiki/How-to-Use) to see what's happening under the hood and this is how it looks for our setup. It's very convenient to see which module links to which while debugging the code.

![Imgur](https://i.imgur.com/Uzsbx9P.png)

## Requirements

You will only need Node.js [installed](https://nodejs.org/en/download/package-manager/) in your environement.


## How to run

```
git clone git@github.com:DumindaWijesinghe/web-audio-api-demo.git
cd web-audio-api-demo
npx http-server ./
```

