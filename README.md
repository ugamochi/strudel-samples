# Strudel Samples

Custom breakbeat pack for Strudel. Load them via:

```javascript
await samples('https://raw.githubusercontent.com/ugamochi/strudel-samples/main/strudel.json')
```

Then trigger loops like:

```javascript
s('br:0').loopAt(1)
s('br:3').scrub('<0 0.25 0.5 0.75>').fit()
```

Files included:
- `br1.wav`
- `br2.wav`
- `br3.wav`
- `br4.wav`
- `br5.wav`
