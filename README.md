# Strudel Samples

Breakbeat pack for Strudel. Load it in two ways:

```javascript
await samples('https://raw.githubusercontent.com/ugamochi/strudel-samples/main/br/strudel.json')
// or the root map (kept for compatibility)
await samples('https://raw.githubusercontent.com/ugamochi/strudel-samples/main/strudel.json')
```

Trigger loops:

```javascript
s('br:0').loopAt(1)   // br1.wav
s('br1').fit()        // alias to br1.wav
s('br1/2').loopAt(1)  // alias to br2.wav for slash-friendly code
```

Files live under `/br`:
- `br1.wav`
- `br2.wav`
- `br3.wav`
- `br4.wav`
- `br5.wav`
