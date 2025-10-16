
# Noise Sample Song

```js
setcpm(50/3) // sets cycles per minute (tempo) 

//$:s("noise:0").loop(5) 
// plays sample "noise:0" and loops it 5 times

//$:s("noise:0")
// .scrub("{0.1!2 .25@6 0.4!2 .25@6 }%8") // scrubs through sample at 10%, 25%, 40%; repeats & stretches pattern over 8 cycles
// .pan("1 0.5")

//$:s("noise*6")
// .speed("1 2 4 1 -2 -4") // varies playback speed: forward, reverse, faster/slower
// .gain(1)
```
