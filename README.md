# Strudel Samples

Five breakbeats packaged for Strudel. Load them via:

```javascript
await samples('github:ugamochi/strudel-samples')
```

Usage examples:

```javascript
s('br:0').loopAt(1)   // br1.wav
s('br2').fit()        // br2.wav
s('br1/2').scrub('<0 0.25 0.5 0.75>').fit()
```

Files live under the `breaks/` folder:
- `br1.wav`
- `br2.wav`
- `br3.wav`
- `br4.wav`
- `br5.wav`
