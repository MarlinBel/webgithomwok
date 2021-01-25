<template lang = "pug">
    .p5Canvas
</template>

<script>
import P5 from 'p5';

export default {
  data() {
    return {
      p5Canvas: null,
    }
  },
  created() {
    const sketch = p5 => {
        let pos = 0 , pos2 = 0, i=0;
        let starrsa = [], starrsb = [], starrsr = [];
        p5.setup = () => {
            // bg = loadImage('https://upload.cc/i1/2021/01/15/XoOeD4.jpg');
            // bg = loadImage(src='123.jpg');
            p5.createCanvas(1520, 2200);
            p5.noStroke();
            p5.clear();
            for(i = 0 ; i < 500; i++){
              let r = p5.random(6,9);
              let a = p5.random(0,1520);
              let b = p5.random(-10000,10000);
              starrsa[i] = a;
              starrsb[i] = b;
              starrsr[i] = r;
              p5.fill(255);
              p5.ellipse(a, pos2+b, r, r);
            }

        }

        p5.draw = () => {
          p5.clear();
          for(i = 0 ; i < 500; i++){
              p5.fill(255);
              p5.ellipse(starrsa[i], pos2+starrsb[i], starrsr[i], starrsr[i]);
            }
        }

        p5.mouseWheel = (event) => {
          //move the square according to the vertical scroll amount
          // pos += (event.delta/4);
          pos2 -= (event.delta/2);
          
        }

        p5.mousePressed = () => {
          p5.remove(); // remove whole sketch on mouse press
        }
    }

    this.p5Canvas = new P5(sketch, 'p5Canvas');
  },
  unmounted() {
    this.p5Canvas = null;
  },
}
</script>

<style lang = "sass">

.p5Canvas
    position: fixed
    z-index: 1
    /* border: 1px solid blue */
    top: 0%
    /* background-image: url('https://upload.cc/i1/2020/12/21/jQpAUT.jpg') */
</style>