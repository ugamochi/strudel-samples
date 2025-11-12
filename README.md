# Strudel Samples

Breakbeat pack for Strudel. Load whichever map you need:

```javascript
await samples('github:ugamochi/strudel-samples')        // full pack (br + aliases)
await samples('github:ugamochi/strudel-samples/br')     // same as above, scoped to /br
await samples('github:ugamochi/strudel-samples/br1')    // just br1.wav
await samples('github:ugamochi/strudel-samples/br2')    // just br2.wav (also alias br1/2)
```

Trigger loops:

```javascript
s('br:0').loopAt(1)   // br1.wav from the pack map
s('br1').fit()        // alias to br1.wav
s('br1/2').loopAt(1)  // alias to br2.wav
```

Files live under `/br`:
- `br1.wav`
- `br2.wav`
- `br3.wav`
- `br4.wav`
- `br5.wav`
