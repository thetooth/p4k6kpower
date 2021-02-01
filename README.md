# BM Pocket 4k/6k single power source compatibility table 🔥🚒

- ✔️ Confirmed working 
- ❓ Works in theory but not extensively tested
- 🛑 Known camera murderer

| Battery Type | Battery Adaptor    | HDMI Cable         | Monitor            | Monitor Adaptor    | *Result*           |
| ------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ |
| V Lock       | Hedbox UNIX-BM     | Smallrig 20cm      | Portkeys BM5       | D-TAP              | ✔️                  |

If you would like to list your combination here open a issue [here](https://github.com/thetooth/p4k6kpower/issues) or submit a PR.

## What causes the HDMI to die in the first place???

### Ground loops

Often the problem is sighted as a "ground loop" which while less than ideal, should not result in damage except in extremely rare circumstances where the monitor or cameras polarity has been reversed. Take for example your computer and it's monitor, a ground loop exists between the video input and power board they share, yet they continue to function for many years.

If a fault does occur, the result is often dramatic, the HDMI cable will get hot and the monitor might catch fire 🔥🔥🔥, to be sure equipment is not in a faulted state, carefully check for any arcing (⚡) as the HDMI connector is inserted and follow [ARRIs documentation](https://www.arri.com/resource/blob/194752/26e7a4ca07e7a8f0ce038b23109b216c/download-technical-information-data.pdf) on connection sequencing.

### Gremlins/transients/cheap shit

What seems to be more common however is electrical gremlins within monitors or cables causing current to travel via the signal wires of the HDMI connector, cooking the camera from the inside out. 🍖 These kinds of faults leave no visual damage but result in the camera unable to provide video out without repair or replacement of the main PCB.

However, mitigating this problem is very straight forward. Only use decent quality cables and monitors, in particular ensure you are using a quality v lock battery plate, the ones that have a dozen different voltage outputs are the worst when it comes to safety.
