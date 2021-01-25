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
        let pos = 0 , pos1 = 0;
        p5.setup = () => {
            // bg = loadImage('https://upload.cc/i1/2021/01/15/XoOeD4.jpg');
            // bg = loadImage(src='123.jpg');
            p5.createCanvas(1520, 2200);
            p5.noStroke();
        }

        p5.draw = () => {
          p5.clear()
          p5.fill(255);
          p5.ellipse(252, pos-1120, 10, 10);
          p5.ellipse(600, pos-1100, 10, 10);
          p5.ellipse(100, pos-1680, 8, 8);
          p5.ellipse(1300, pos-1600, 10, 10);
          p5.ellipse(800, pos-1500, 10, 10);
          p5.ellipse(1400, pos-1090, 8, 8);
          p5.ellipse(1100, pos-1350, 10, 10);
          p5.ellipse(400, pos-1480, 6, 6);
          p5.ellipse(130, pos-1900, 10, 10);
          p5.ellipse(450, pos-1880, 8, 8);
          p5.ellipse(950, pos-1790, 10, 10);


          p5.ellipse(280, pos-110, 10, 10);
          p5.ellipse(610, pos-210, 8, 8);
          p5.ellipse(100, pos-680, 10, 10);
          p5.ellipse(1300, pos-600, 10, 10);
          p5.ellipse(800, pos-500, 10, 10);
          p5.ellipse(1390, pos-190, 10, 10);
          p5.ellipse(1100, pos-350, 6, 6);
          p5.ellipse(400, pos-480, 10, 10);
          p5.ellipse(130, pos-900, 10, 10);
          p5.ellipse(450, pos-880, 10, 10);
          p5.ellipse(950, pos-790, 8, 8);

          p5.ellipse(0, pos+630, 20, 20);
          p5.ellipse(1520, pos+230, 20, 20);
          p5.ellipse(252, pos+120, 10, 10);
          p5.ellipse(600, pos+100, 6, 6);
          p5.ellipse(100, pos+680, 10, 10);
          p5.ellipse(1300, pos+600, 10, 10);
          p5.ellipse(800, pos+500, 10, 10);
          p5.ellipse(1400, pos+90, 8, 8);
          p5.ellipse(1100, pos+350, 10, 10);
          p5.ellipse(400, pos+480, 10, 10);
          p5.ellipse(130, pos+900, 10, 10);
          p5.ellipse(450, pos+880, 8, 8);
          p5.ellipse(950, pos+790, 10, 10);
          p5.ellipse(850, pos+300, 8, 8);
          p5.ellipse(1350, pos+450, 6, 6);

          p5.ellipse(252, pos+1120, 8, 8);
          p5.ellipse(600, pos+1100, 10, 10);
          p5.ellipse(100, pos+1680, 10, 10);
          p5.ellipse(1300, pos+1600, 8, 8);
          p5.ellipse(800, pos+1500, 10, 10);
          p5.ellipse(1400, pos+1090, 10, 10);
          p5.ellipse(1100, pos+1350, 10, 10);
          p5.ellipse(400, pos+1480, 10, 10);
          p5.ellipse(130, pos+1900, 6, 6);
          p5.ellipse(450, pos+1880, 8, 8);
          p5.ellipse(950, pos+1790, 10, 10);

          p5.ellipse(252, pos+2220, 10, 10);
          p5.ellipse(600, pos+2100, 8, 8);
          p5.ellipse(100, pos+2680, 10, 10);
          p5.ellipse(1300, pos+2710, 10, 10);
          p5.ellipse(800, pos+2500, 10, 10);
          p5.ellipse(1400, pos+2590, 10, 10);
          p5.ellipse(1100, pos+2350, 10, 10);
          p5.ellipse(400, pos+2480, 8, 8);
          p5.ellipse(130, pos+2900, 10, 10);
          p5.ellipse(450, pos+2880, 10, 10);
          p5.ellipse(950, pos+2790, 10, 10);          
          // p5.fill(255);
          // p5.ellipse(252, pos1, 72, 72);
          p5.ellipse(120, pos1-1100, 8, 8);
          p5.ellipse(690, pos1-1300, 7, 7);
          p5.ellipse(230, pos1-1410, 4, 4);
          p5.ellipse(980, pos1-1700, 6, 6);
          p5.ellipse(640, pos1-170, 7, 7);
          p5.ellipse(1310, pos1-1350, 6, 6);
          p5.ellipse(980, pos1-1100, 7, 7);
          p5.ellipse(500, pos1-1250, 6, 6);
          p5.ellipse(110, pos1-980, 7, 7);
          p5.ellipse(610, pos1-1550, 5, 5);
          p5.ellipse(1000, pos1-1800, 6, 6);
          p5.ellipse(400, pos1-1650, 5, 5);
          p5.ellipse(590, pos1-1400, 7, 7);
          p5.ellipse(410, pos1-1260, 6, 6);
          p5.ellipse(1070, pos1-1500, 6, 6);
          p5.ellipse(1190, pos-1200, 6, 6);
          
          p5.ellipse(120, pos1-120, 8, 8);
          p5.ellipse(690, pos1-250, 7, 7);
          p5.ellipse(230, pos1-410, 4, 4);
          p5.ellipse(980, pos1-690, 6, 6);
          p5.ellipse(640, pos1-720, 7, 7);
          p5.ellipse(1310, pos1-300, 6, 6);
          p5.ellipse(980, pos1-200, 7, 7);
          p5.ellipse(500, pos1-250, 6, 6);
          p5.ellipse(110, pos1-1100, 7, 7);
          p5.ellipse(610, pos1-550, 5, 5);
          p5.ellipse(1000, pos1-790, 6, 6);
          p5.ellipse(400, pos1-670, 5, 5);
          p5.ellipse(590, pos1-390, 7, 7);
          p5.ellipse(410, pos1-250, 6, 6);
          p5.ellipse(1070, pos1-500, 6, 6);
          p5.ellipse(1190, pos-200, 6, 6);
          
          p5.ellipse(100, pos1+120, 6, 6);
          p5.ellipse(700, pos1+250, 7, 7);
          p5.ellipse(200, pos1+410, 4, 4);
          p5.ellipse(1010, pos1+690, 6, 6);
          p5.ellipse(610, pos1+720, 7, 7);
          p5.ellipse(1450, pos1+300, 6, 6);
          p5.ellipse(1070, pos1+200, 7, 7);
          p5.ellipse(450, pos1+250, 6, 6);
          p5.ellipse(90, pos1+1100, 7, 7);
          p5.ellipse(650, pos1+550, 5, 5);
          p5.ellipse(950, pos1+790, 6, 6);
          p5.ellipse(370, pos1+670, 5, 5);
          p5.ellipse(550, pos1+390, 7, 7);
          p5.ellipse(450, pos1+250, 6, 6);
          p5.ellipse(1150, pos1+500, 6, 6);
          p5.ellipse(1240, pos+200, 6, 6);

          p5.ellipse(100, pos1+1120, 6, 6);
          p5.ellipse(700, pos1+1350, 7, 7);
          p5.ellipse(200, pos1+1410, 4, 4);
          p5.ellipse(1010, pos1+1690, 6, 6);
          p5.ellipse(610, pos1+1720, 7, 7);
          p5.ellipse(1450, pos1+1300, 6, 6);
          p5.ellipse(1070, pos1+1150, 7, 7);
          p5.ellipse(450, pos1+1250, 6, 6);
          p5.ellipse(90, pos1+1900, 7, 7);
          p5.ellipse(650, pos1+1550, 5, 5);
          p5.ellipse(950, pos1+1790, 6, 6);
          p5.ellipse(370, pos1+1670, 5, 5);
          p5.ellipse(550, pos1+1390, 7, 7);
          p5.ellipse(450, pos1+1250, 6, 6);
          p5.ellipse(1150, pos1+1500, 6, 6);
          p5.ellipse(1240, pos+1230, 6, 6);

          p5.ellipse(100, pos1+2100, 6, 6);
          p5.ellipse(700, pos1+2340, 7, 7);
          p5.ellipse(200, pos1+2400, 4, 4);
          p5.ellipse(1010, pos1+2700, 6, 6);
          p5.ellipse(610, pos1+2730, 7, 7);
          p5.ellipse(1450, pos1+2330, 6, 6);
          p5.ellipse(1070, pos1+2200, 7, 7);
          p5.ellipse(450, pos1+2300, 6, 6);
          p5.ellipse(90, pos1+2750, 7, 7);
          p5.ellipse(650, pos1+2600, 5, 5);
          p5.ellipse(950, pos1+2810, 6, 6);
          p5.ellipse(370, pos1+2700, 5, 5);
          p5.ellipse(550, pos1+2400, 7, 7);
          p5.ellipse(450, pos1+2270, 6, 6);
          p5.ellipse(1150, pos1+2570, 6, 6);
          p5.ellipse(1240, pos+2260, 6, 6);

          p5.ellipse(150, pos-2150, 6, 6);
          p5.ellipse(70, pos1-2250, 7, 7);
          p5.ellipse(370, pos1-2190, 4, 4);
          p5.ellipse(200, pos1-2550, 6, 6);
          p5.ellipse(130, pos-2480, 5, 5);
          p5.ellipse(270, pos1-2270, 6, 6);
          p5.ellipse(450, pos-2150, 5, 5);
          p5.ellipse(390, pos-2340, 5, 5);
          p5.ellipse(410, pos1-2360, 4, 4);
          p5.ellipse(570, pos1-2240, 5, 5);
          p5.ellipse(590, pos-2270, 7, 7);
          p5.ellipse(320, pos-2530, 6, 6);
          p5.ellipse(310, pos1-2440, 3, 3);
          p5.ellipse(260, pos1-1770, 6, 6);
          p5.ellipse(270, pos-2650, 6, 6);
          p5.ellipse(50, pos1-2450, 4, 3);
          p5.ellipse(540, pos-2590, 7, 7);
          p5.ellipse(700, pos1-2425, 4, 3);
          p5.ellipse(950, pos1-2410, 5, 4);
          p5.ellipse(900, pos1-2140, 5, 5);
          p5.ellipse(1020, pos-2115, 7, 7);
          p5.ellipse(1010, pos-2530, 6, 6);
          p5.ellipse(810, pos1-2605, 6, 6);
          p5.ellipse(835, pos-1737, 8, 8);
          p5.ellipse(760, pos1-1885, 5, 5);
          p5.ellipse(1130, pos1-2100, 5, 5);
          p5.ellipse(1360, pos1-2230, 3, 3);
          p5.ellipse(1290, pos1-2360, 3, 3);
          p5.ellipse(1000, pos1-2300, 4, 4);
          p5.ellipse(790, pos-2160, 5, 5);
          p5.ellipse(1400, pos-2737, 8, 8);
          p5.ellipse(1220, pos1-2710, 4, 4);
          p5.ellipse(1480, pos1-2580, 6, 6);
          p5.ellipse(1160, pos1-2290, 5, 5);
          p5.ellipse(1005, pos1-2526, 3, 3);
          p5.ellipse(1355, pos1-2446, 5, 6);
          p5.ellipse(1485, pos1-2440, 3, 3);
          p5.ellipse(1510, pos-2480, 6, 6);
          p5.ellipse(1510, pos1-2150, 6, 6);
          p5.ellipse(1260, pos1-1780, 2, 2);

          p5.ellipse(150, pos-1150, 6, 6);
          p5.ellipse(70, pos1-1250, 7, 7);
          p5.ellipse(370, pos1-790, 4, 4);
          p5.ellipse(200, pos1-1550, 6, 6);
          p5.ellipse(130, pos-1480, 5, 5);
          p5.ellipse(270, pos1-1270, 6, 6);
          p5.ellipse(450, pos-1150, 5, 5);
          p5.ellipse(390, pos-1340, 5, 5);
          p5.ellipse(410, pos1-1360, 4, 4);
          p5.ellipse(570, pos1-1240, 5, 5);
          p5.ellipse(590, pos-1270, 7, 7);
          p5.ellipse(320, pos-1530, 6, 6);
          p5.ellipse(310, pos1-1440, 3, 3);
          p5.ellipse(260, pos1-770, 6, 6);
          p5.ellipse(270, pos-1650, 6, 6);
          p5.ellipse(50, pos1-1450, 4, 3);
          p5.ellipse(540, pos-1590, 7, 7);
          p5.ellipse(700, pos1-1425, 4, 3);
          p5.ellipse(950, pos1-1410, 5, 4);
          p5.ellipse(900, pos1-1140, 5, 5);
          p5.ellipse(1020, pos-1115, 7, 7);
          p5.ellipse(1010, pos-1530, 6, 6);
          p5.ellipse(810, pos1-1605, 6, 6);
          p5.ellipse(835, pos-837, 8, 8);
          p5.ellipse(760, pos1-985, 5, 5);
          p5.ellipse(1130, pos1-1100, 5, 5);
          p5.ellipse(1360, pos1-1230, 3, 3);
          p5.ellipse(1290, pos1-1360, 3, 3);
          p5.ellipse(1000, pos1-1300, 4, 4);
          p5.ellipse(790, pos-1160, 5, 5);
          p5.ellipse(1400, pos-1737, 8, 8);
          p5.ellipse(1220, pos1-1710, 4, 4);
          p5.ellipse(1480, pos1-1580, 6, 6);
          p5.ellipse(1160, pos1-1290, 5, 5);
          p5.ellipse(1005, pos1-1526, 3, 3);
          p5.ellipse(1355, pos1-1446, 5, 6);
          p5.ellipse(1485, pos1-1440, 3, 3);
          p5.ellipse(1510, pos-1480, 6, 6);
          p5.ellipse(1510, pos1-950, 6, 6);
          p5.ellipse(1260, pos1-880, 2, 2);
          
          p5.ellipse(150, pos-150, 6, 6);
          p5.ellipse(70, pos1-250, 7, 7);
          p5.ellipse(370, pos1-190, 4, 4);
          p5.ellipse(200, pos1-550, 6, 6);
          p5.ellipse(130, pos-480, 5, 5);
          p5.ellipse(270, pos1-270, 6, 6);
          p5.ellipse(450, pos-150, 5, 5);
          p5.ellipse(390, pos-340, 5, 5);
          p5.ellipse(410, pos1-360, 4, 4);
          p5.ellipse(570, pos1-240, 5, 5);
          p5.ellipse(590, pos-270, 7, 7);
          p5.ellipse(320, pos-530, 6, 6);
          p5.ellipse(310, pos1-440, 3, 3);
          p5.ellipse(260, pos1-770, 6, 6);
          p5.ellipse(270, pos-650, 6, 6);
          p5.ellipse(50, pos1-450, 4, 3);
          p5.ellipse(540, pos-590, 7, 7);
          p5.ellipse(700, pos1-425, 4, 3);
          p5.ellipse(950, pos1-410, 5, 4);
          p5.ellipse(900, pos1-140, 5, 5);
          p5.ellipse(1020, pos-115, 7, 7);
          p5.ellipse(1010, pos-530, 6, 6);
          p5.ellipse(810, pos1-605, 6, 6);
          p5.ellipse(835, pos-737, 8, 8);
          p5.ellipse(760, pos1-85, 5, 5);
          p5.ellipse(1130, pos1-100, 5, 5);
          p5.ellipse(1360, pos1-230, 3, 3);
          p5.ellipse(1290, pos1-360, 3, 3);
          p5.ellipse(1000, pos1-300, 4, 4);
          p5.ellipse(790, pos-160, 5, 5);
          p5.ellipse(1400, pos-737, 8, 8);
          p5.ellipse(1220, pos1-710, 4, 4);
          p5.ellipse(1480, pos1-580, 6, 6);
          p5.ellipse(1160, pos1-290, 5, 5);
          p5.ellipse(1005, pos1-526, 3, 3);
          p5.ellipse(1355, pos1-446, 5, 6);
          p5.ellipse(1485, pos1-440, 3, 3);
          p5.ellipse(1510, pos-480, 6, 6);
          p5.ellipse(1510, pos1-150, 6, 6);
          p5.ellipse(1260, pos1-80, 2, 2);

          p5.ellipse(150, pos+150, 6, 6);
          p5.ellipse(70, pos1+250, 7, 7);
          p5.ellipse(370, pos1+190, 4, 4);
          p5.ellipse(200, pos1+550, 6, 6);
          p5.ellipse(130, pos+480, 5, 5);
          p5.ellipse(270, pos1+270, 6, 6);
          p5.ellipse(450, pos+150, 5, 5);
          p5.ellipse(390, pos+340, 5, 5);
          p5.ellipse(410, pos1+360, 4, 4);
          p5.ellipse(570, pos1+240, 5, 5);
          p5.ellipse(590, pos+270, 7, 7);
          p5.ellipse(320, pos+530, 6, 6);
          p5.ellipse(310, pos1+440, 3, 3);
          p5.ellipse(260, pos1+770, 6, 6);
          p5.ellipse(270, pos+650, 6, 6);
          p5.ellipse(50, pos1+450, 4, 3);
          p5.ellipse(540, pos+590, 7, 7);
          p5.ellipse(700, pos1+425, 4, 3);
          p5.ellipse(950, pos1+410, 5, 4);
          p5.ellipse(900, pos1+140, 5, 5);
          p5.ellipse(1020, pos+115, 7, 7);
          p5.ellipse(1010, pos+530, 6, 6);
          p5.ellipse(810, pos1+605, 6, 6);
          p5.ellipse(835, pos+737, 8, 8);
          p5.ellipse(760, pos1+85, 5, 5);
          p5.ellipse(1130, pos1+100, 5, 5);
          p5.ellipse(1360, pos1+230, 3, 3);
          p5.ellipse(1290, pos1+360, 3, 3);
          p5.ellipse(1000, pos1+300, 4, 4);
          p5.ellipse(790, pos+160, 5, 5);
          p5.ellipse(1400, pos+737, 8, 8);
          p5.ellipse(1220, pos1+710, 4, 4);
          p5.ellipse(1480, pos1+580, 6, 6);
          p5.ellipse(1160, pos1+290, 5, 5);
          p5.ellipse(1005, pos1+526, 3, 3);
          p5.ellipse(1355, pos1+446, 5, 6);
          p5.ellipse(1485, pos1+440, 3, 3);
          p5.ellipse(1510, pos+480, 6, 6);
          p5.ellipse(1510, pos1+150, 6, 6);
          p5.ellipse(1260, pos1+80, 2, 2);

          p5.ellipse(150, pos+850, 6, 6);
          p5.ellipse(70, pos1+1250, 7, 7);
          p5.ellipse(370, pos1+990, 4, 4);
          p5.ellipse(200, pos1+1550, 6, 6);
          p5.ellipse(130, pos+1480, 5, 5);
          p5.ellipse(270, pos1+1270, 6, 6);
          p5.ellipse(450, pos+870, 5, 5);
          p5.ellipse(390, pos+1340, 5, 5);
          p5.ellipse(410, pos1+1360, 4, 4);
          p5.ellipse(570, pos1+1240, 5, 5);
          p5.ellipse(590, pos+1270, 7, 7);
          p5.ellipse(320, pos+1530, 6, 6);
          p5.ellipse(310, pos1+1440, 3, 3);
          p5.ellipse(260, pos1+1770, 6, 6);
          p5.ellipse(270, pos+1650, 6, 6);
          p5.ellipse(50, pos1+1450, 4, 3);
          p5.ellipse(540, pos+1590, 7, 7);
          p5.ellipse(700, pos1+1425, 4, 3);
          p5.ellipse(950, pos1+1410, 5, 4);
          p5.ellipse(900, pos1+940, 5, 5);
          p5.ellipse(1020, pos+935, 7, 7);
          p5.ellipse(1010, pos+1530, 6, 6);
          p5.ellipse(810, pos1+1605, 6, 6);
          p5.ellipse(835, pos+1737, 8, 8);
          p5.ellipse(760, pos1+1085, 5, 5);
          p5.ellipse(1130, pos1+990, 5, 5);
          p5.ellipse(1360, pos1+1230, 3, 3);
          p5.ellipse(1290, pos1+1360, 3, 3);
          p5.ellipse(1000, pos1+1300, 4, 4);
          p5.ellipse(790, pos+860, 5, 5);
          p5.ellipse(1400, pos+1737, 8, 8);
          p5.ellipse(1220, pos1+1710, 4, 4);
          p5.ellipse(1480, pos1+1580, 6, 6);
          p5.ellipse(1160, pos1+1290, 5, 5);
          p5.ellipse(1005, pos1+1526, 3, 3);
          p5.ellipse(1355, pos1+1446, 5, 6);
          p5.ellipse(1485, pos1+1440, 3, 3);
          p5.ellipse(1510, pos+1480, 6, 6);
          p5.ellipse(1510, pos1+850, 6, 6);
          p5.ellipse(1260, pos1+880, 2, 2);

          p5.ellipse(150, pos+1950, 6, 6);
          p5.ellipse(70, pos1+2250, 7, 7);
          p5.ellipse(370, pos1+1990, 4, 4);
          p5.ellipse(200, pos1+2550, 6, 6);
          p5.ellipse(130, pos+2480, 5, 5);
          p5.ellipse(270, pos1+2270, 6, 6);
          p5.ellipse(450, pos+1970, 5, 5);
          p5.ellipse(390, pos+2340, 5, 5);
          p5.ellipse(410, pos1+2360, 4, 4);
          p5.ellipse(570, pos1+2240, 5, 5);
          p5.ellipse(590, pos+2270, 7, 7);
          p5.ellipse(320, pos+2530, 6, 6);
          p5.ellipse(310, pos1+2440, 3, 3);
          p5.ellipse(260, pos1+2770, 6, 6);
          p5.ellipse(270, pos+2650, 6, 6);
          p5.ellipse(50, pos1+2450, 4, 3);
          p5.ellipse(540, pos+2590, 7, 7);
          p5.ellipse(700, pos1+2425, 4, 3);
          p5.ellipse(950, pos1+2410, 5, 4);
          p5.ellipse(900, pos1+2140, 5, 5);
          p5.ellipse(1020, pos+935, 7, 7);
          p5.ellipse(1010, pos+2530, 6, 6);
          p5.ellipse(810, pos1+2605, 6, 6);
          p5.ellipse(835, pos+2737, 8, 8);
          p5.ellipse(760, pos1+2085, 5, 5);
          p5.ellipse(1130, pos1+1990, 5, 5);
          p5.ellipse(1360, pos1+2230, 3, 3);
          p5.ellipse(1290, pos1+2360, 3, 3);
          p5.ellipse(1000, pos1+2300, 4, 4);
          p5.ellipse(790, pos+2160, 5, 5);
          p5.ellipse(1400, pos+2737, 8, 8);
          p5.ellipse(1220, pos1+2710, 4, 4);
          p5.ellipse(1480, pos1+2580, 6, 6);
          p5.ellipse(1160, pos1+2290, 5, 5);
          p5.ellipse(1005, pos1+2526, 3, 3);
          p5.ellipse(1355, pos1+2446, 5, 6);
          p5.ellipse(1485, pos1+2440, 3, 3);
          p5.ellipse(1510, pos+2480, 6, 6);
          p5.ellipse(1510, pos1+2150, 6, 6);
          p5.ellipse(1260, pos1+1980, 2, 2);

          
          p5.ellipse(150, pos+3150, 6, 6);
          p5.ellipse(70, pos1+3250, 7, 7);
          p5.ellipse(370, pos1+3190, 4, 4);
          p5.ellipse(200, pos1+3550, 6, 6);
          p5.ellipse(130, pos+3480, 5, 5);
          p5.ellipse(270, pos1+3270, 6, 6);
          p5.ellipse(450, pos+3150, 5, 5);
          p5.ellipse(390, pos+3340, 5, 5);
          p5.ellipse(410, pos1+3360, 4, 4);
          p5.ellipse(570, pos1+3240, 5, 5);
          p5.ellipse(590, pos+3270, 7, 7);
          p5.ellipse(320, pos+3530, 6, 6);
          p5.ellipse(310, pos1+3440, 3, 3);
          p5.ellipse(260, pos1+3770, 6, 6);
          p5.ellipse(270, pos+3650, 6, 6);
          p5.ellipse(50, pos1+3450, 4, 3);
          p5.ellipse(540, pos+3590, 7, 7);
          p5.ellipse(700, pos1+3425, 4, 3);
          p5.ellipse(950, pos1+3410, 5, 4);
          p5.ellipse(900, pos1+3140, 5, 5);
          p5.ellipse(1020, pos+3115, 7, 7);
          p5.ellipse(1010, pos+3530, 6, 6);
          p5.ellipse(810, pos1+3605, 6, 6);
          p5.ellipse(835, pos+3737, 8, 8);
          p5.ellipse(760, pos1+3085, 5, 5);
          p5.ellipse(1130, pos1+3100, 5, 5);
          p5.ellipse(1360, pos1+3230, 3, 3);
          p5.ellipse(1290, pos1+3360, 3, 3);
          p5.ellipse(1000, pos1+3300, 4, 4);
          p5.ellipse(790, pos+3160, 5, 5);
          p5.ellipse(1400, pos+3737, 8, 8);
          p5.ellipse(1220, pos1+3710, 4, 4);
          p5.ellipse(1480, pos1+3580, 6, 6);
          p5.ellipse(1160, pos1+3290, 5, 5);
          p5.ellipse(1005, pos1+3526, 3, 3);
          p5.ellipse(1355, pos1+3446, 5, 6);
          p5.ellipse(1485, pos1+3440, 3, 3);
          p5.ellipse(1510, pos+3480, 6, 6);
          p5.ellipse(1510, pos1+3150, 6, 6);
          p5.ellipse(1260, pos1+3080, 2, 2);

        }

        p5.mouseWheel = (event) => {
          //move the square according to the vertical scroll amount
          pos -= (event.delta/3);
          pos1 -= (event.delta/2);
          
          //uncomment to block page scrolling
          //return false;
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
    position: fixed
    z-index: 1
    /* border: 1px solid blue */
    top: 0%
    /* background-image: url('https://upload.cc/i1/2020/12/21/jQpAUT.jpg') */
</style>