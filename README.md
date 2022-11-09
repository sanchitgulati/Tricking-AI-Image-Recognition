# Tricking AI Image Recognition 
## _How many pixels does it take to fool RNET classifier?_
### Answer : Not Many!
### Inspiration : [YouTube Video by Computerphile](https://www.youtube.com/watch?v=gGIiechWEFs)

### Classification Model Details
```py
weights = ResNet50_Weights.DEFAULT
model = resnet50
```

### Dataset
```
https://huggingface.co/datasets/jamescalam/unsplash-25k-photos
```

### Image 1 
Initial Prediction: monarch            |  pixels_modified: 687         |  After Modification: ringlet
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/0_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/0_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/0_modified.jpeg?raw=true)

### Image 2 
Initial Prediction: head cabbage            |  pixels_modified: 154         |  After Modification: ice cream
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/1_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/1_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/1_modified.jpeg?raw=true)

### Image 3 
Initial Prediction: pay-phone            |  pixels_modified: 200         |  After Modification: cash machine
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/2_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/2_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/2_modified.jpeg?raw=true)

### Image 4 
Initial Prediction: cliff            |  pixels_modified: 136         |  After Modification: promontory
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/3_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/3_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/3_modified.jpeg?raw=true)

### Image 5 
Initial Prediction: seashore            |  pixels_modified: 276         |  After Modification: promontory
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/4_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/4_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/4_modified.jpeg?raw=true)

### Image 6 
Initial Prediction: mountain tent            |  pixels_modified: 160         |  After Modification: yurt
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/5_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/5_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/5_modified.jpeg?raw=true)

### Image 7 
Initial Prediction: castle            |  pixels_modified: 673         |  After Modification: palace
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/6_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/6_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/6_modified.jpeg?raw=true)

### Image 8 
Initial Prediction: bubble            |  pixels_modified: 209         |  After Modification: fountain
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/7_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/7_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/7_modified.jpeg?raw=true)

### Image 9 
Initial Prediction: volcano            |  pixels_modified: 196         |  After Modification: torch
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/8_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/8_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/8_modified.jpeg?raw=true)

### Image 10 
Initial Prediction: alp            |  pixels_modified: 472         |  After Modification: mountain tent
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/9_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/9_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/9_modified.jpeg?raw=true)

### Image 11 
Initial Prediction: common iguana            |  pixels_modified: 595         |  After Modification: green lizard
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/10_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/10_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/10_modified.jpeg?raw=true)

### Image 12 
Initial Prediction: cloak            |  pixels_modified: 47         |  After Modification: abaya
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/11_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/11_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/11_modified.jpeg?raw=true)

### Image 13 
Initial Prediction: volcano            |  pixels_modified: 173         |  After Modification: alp
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/12_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/12_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/12_modified.jpeg?raw=true)

### Image 14 
Initial Prediction: torch            |  pixels_modified: 131         |  After Modification: beacon
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/13_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/13_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/13_modified.jpeg?raw=true)

### Image 15 
Initial Prediction: wool            |  pixels_modified: 162         |  After Modification: swab
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/14_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/14_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/14_modified.jpeg?raw=true)

### Image 16 
Initial Prediction: jellyfish            |  pixels_modified: 336         |  After Modification: isopod
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/15_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/15_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/15_modified.jpeg?raw=true)

### Image 17 
Initial Prediction: vase            |  pixels_modified: 125         |  After Modification: pot
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/16_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/16_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/16_modified.jpeg?raw=true)

### Image 18 
Initial Prediction: carousel            |  pixels_modified: 298         |  After Modification: water snake
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/17_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/17_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/17_modified.jpeg?raw=true)

### Image 19 
Initial Prediction: vase            |  pixels_modified: 557         |  After Modification: pot
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/18_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/18_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/18_modified.jpeg?raw=true)

### Image 20 
Initial Prediction: goose            |  pixels_modified: 255         |  After Modification: lakeside
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/19_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/19_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/19_modified.jpeg?raw=true)

### Image 21 
Initial Prediction: golden retriever            |  pixels_modified: 382         |  After Modification: tennis ball
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/20_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/20_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/20_modified.jpeg?raw=true)

### Image 22 
Initial Prediction: mountain tent            |  pixels_modified: 744         |  After Modification: valley
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/21_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/21_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/21_modified.jpeg?raw=true)

### Image 23 
Initial Prediction: seashore            |  pixels_modified: 185         |  After Modification: sandbar
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/22_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/22_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/22_modified.jpeg?raw=true)

### Image 24 
Initial Prediction: alp            |  pixels_modified: 486         |  After Modification: valley
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/23_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/23_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/23_modified.jpeg?raw=true)

### Image 25 
Initial Prediction: hamster            |  pixels_modified: 183         |  After Modification: bath towel
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/24_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/24_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/24_modified.jpeg?raw=true)

### Image 26 
Initial Prediction: alp            |  pixels_modified: 719         |  After Modification: ski
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/25_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/25_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/25_modified.jpeg?raw=true)

### Image 27 
Initial Prediction: jellyfish            |  pixels_modified: 254         |  After Modification: bubble
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/26_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/26_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/26_modified.jpeg?raw=true)

### Image 28 
Initial Prediction: gas pump            |  pixels_modified: 290         |  After Modification: traffic light
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/27_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/27_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/27_modified.jpeg?raw=true)

### Image 29 
Initial Prediction: promontory            |  pixels_modified: 177         |  After Modification: seashore
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/28_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/28_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/28_modified.jpeg?raw=true)

### Image 30 
Initial Prediction: coral reef            |  pixels_modified: 283         |  After Modification: scuba diver
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/29_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/29_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/29_modified.jpeg?raw=true)

### Image 31 
Initial Prediction: alp            |  pixels_modified: 536         |  After Modification: valley
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/30_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/30_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/30_modified.jpeg?raw=true)

### Image 32 
Initial Prediction: seashore            |  pixels_modified: 259         |  After Modification: lakeside
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/31_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/31_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/31_modified.jpeg?raw=true)

### Image 33 
Initial Prediction: Pembroke            |  pixels_modified: 773         |  After Modification: Cardigan
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/32_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/32_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/32_modified.jpeg?raw=true)

### Image 34 
Initial Prediction: Cardigan            |  pixels_modified: 290         |  After Modification: Pembroke
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/33_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/33_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/33_modified.jpeg?raw=true)

### Image 35 
Initial Prediction: alp            |  pixels_modified: 162         |  After Modification: volcano
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/34_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/34_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/34_modified.jpeg?raw=true)

### Image 36 
Initial Prediction: cocker spaniel            |  pixels_modified: 384         |  After Modification: Sussex spaniel
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/35_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/35_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/35_modified.jpeg?raw=true)

### Image 37 
Initial Prediction: sea lion            |  pixels_modified: 325         |  After Modification: otter
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/36_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/36_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/36_modified.jpeg?raw=true)

### Image 38 
Initial Prediction: pot            |  pixels_modified: 140         |  After Modification: spider web
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/37_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/37_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/37_modified.jpeg?raw=true)

### Image 39 
Initial Prediction: torch            |  pixels_modified: 153         |  After Modification: sleeping bag
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/38_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/38_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/38_modified.jpeg?raw=true)

### Image 40 
Initial Prediction: alp            |  pixels_modified: 279         |  After Modification: mountain tent
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/39_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/39_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/39_modified.jpeg?raw=true)

### Image 41 
Initial Prediction: seashore            |  pixels_modified: 289         |  After Modification: lakeside
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/40_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/40_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/40_modified.jpeg?raw=true)

### Image 42 
Initial Prediction: ox            |  pixels_modified: 883         |  After Modification: bison
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/41_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/41_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/41_modified.jpeg?raw=true)

### Image 43 
Initial Prediction: suspension bridge            |  pixels_modified: 166         |  After Modification: pier
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/42_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/42_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/42_modified.jpeg?raw=true)

### Image 44 
Initial Prediction: jellyfish            |  pixels_modified: 136         |  After Modification: sea slug
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/43_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/43_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/43_modified.jpeg?raw=true)

### Image 45 
Initial Prediction: volcano            |  pixels_modified: 487         |  After Modification: mountain tent
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/44_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/44_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/44_modified.jpeg?raw=true)

### Image 46 
Initial Prediction: goldfish            |  pixels_modified: 340         |  After Modification: anemone fish
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/45_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/45_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/45_modified.jpeg?raw=true)

### Image 47 
Initial Prediction: greenhouse            |  pixels_modified: 574         |  After Modification: folding chair
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/46_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/46_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/46_modified.jpeg?raw=true)

### Image 48 
Initial Prediction: greenhouse            |  pixels_modified: 340         |  After Modification: crutch
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/47_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/47_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/47_modified.jpeg?raw=true)

### Image 49 
Initial Prediction: valley            |  pixels_modified: 255         |  After Modification: fountain
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/48_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/48_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/48_modified.jpeg?raw=true)

### Image 50 
Initial Prediction: alp            |  pixels_modified: 983         |  After Modification: valley
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/49_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/49_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/49_modified.jpeg?raw=true)

### Image 51 
Initial Prediction: Indian elephant            |  pixels_modified: 644         |  After Modification: tusker
 :-------------------------:|:-------------------------:|:------------------------
 ![Original](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/50_original.jpeg?raw=true)|![Pixel Mask](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/50_pixel.jpeg?raw=true)|![Modified Image](https://github.com/sanchitgulati/Tricking-AI-Image-Recognition/blob/main/data/50_modified.jpeg?raw=true)

## License
MIT