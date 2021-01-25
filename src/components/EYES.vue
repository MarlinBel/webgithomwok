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
        let pos5 = 0, ii = 0;
        let eyesx = [], eyesy = [], eyesr = [];
        let xx = 0;
        let rr = 10;
        let yy = 300;
        let jj = 0;
        // p5.preload = () => {
        //     bg = loadImage(src='123.jpg');
        // }
        p5.setup = () => {
            // bg = loadImage('https://upload.cc/i1/2021/01/15/XoOeD4.jpg');
            // bg = loadImage(src='123.jpg');
            p5.createCanvas(1520, 2400);
            p5.noStroke();
            for(ii = 0 ; ii < 50; ii++){
              rr = p5.random(100,160);
              eyesr[ii] = rr;

            }
        }

        p5.draw = () => {
            // bg = p5.loadImage('https://upload.cc/i1/2021/01/15/XoOeD4.jpg');
            // p5.image(bg,0,0)
            // p5.background(0,0,0,0);
            p5.clear();
            ii = 0;
            for(yy = 800 ; yy < 1200 ; yy += 120){
              xx = 0;
              for(jj = 0 ; jj < 10; ii++, jj++){
                if(xx == 0){
                  xx = 100;
                }else{
                  xx += 3*eyesr[ii];
                }
                p5.Eye(xx, pos5+yy, eyesr[ii]);
                p5.update(p5.mouseX, p5.mouseY);
                p5.display();
                p5.Eye(xx+eyesr[ii], pos5+yy, eyesr[ii]);
                p5.update(p5.mouseX, p5.mouseY);
                p5.display();
              }
            }
            // for(ii = 0 ; ii < 20; ii++){
            //   p5.Eye(eyesx[ii], pos5+eyesy[ii], eyesr[ii]);
            //   p5.update(p5.mouseX, p5.mouseY);
            //   p5.display();
            //   p5.Eye(eyesx[ii]+eyesr[ii], pos5+eyesy[ii], eyesr[ii]);
            //   p5.update(p5.mouseX, p5.mouseY);
            //   p5.display();
            // }
        }

        p5.Eye = (tx, ty, ts) => {
            let x = tx;
            let y = ty;
            let size = ts;
            let angle = 0;

            p5.update = (mx, my) => {
                angle = p5.atan2(my - y, mx - x);
            };

            p5.display = () => {
                p5.push();
                p5.translate(x, y);
                p5.fill(30);
                p5.ellipse(0, 0, size, size/2);
                p5.rotate(angle);
                p5.fill(252, 163, 17);
                p5.ellipse(size / 4, 0, size / 4, size / 3);
                p5.pop();
            };
        }
        p5.mouseWheel = (event) => {
          //move the square according to the vertical scroll amount
          // pos += (event.delta/4);
          pos5 -= (event.delta);
          
          //uncomment to block page scrolling
          //return false;
        }

        p5.mousePressed = () => {
          p5.remove(); // remove whole sketch on mouse press
        }
    }

    this.p5Canvas = new P5(sketch, 'p5Canvas');
  },
  unmounted () {
    this.p5Canvas = null;
  },
}
</script>

<style lang = "sass">

.p5Canvas
    width: 100%
    position: fixed
    z-index: 70
    /* border: 1px solid blue */
    top: 0%
    /* background-image: url('https://upload.cc/i1/2020/12/21/jQpAUT.jpg') */
</style>