# style-transfer-vgg19
#### Testing out style transfrom methods based on the paper written by L Gatys
---
- The `reference style image` used is **The starry night by Vincent Van Gogh**

  ![The starry night pic](https://github.com/fadh1l/style-transfer-vgg19/blob/main/style2_image.png)

- The `reference content image` is just a picture of some buildings in Astana,Kazakhstan

<img src="https://github.com/fadh1l/style-transfer-vgg19/blob/main/content3_image.png" alt="mypic" style="width:200px; height:200px"/>

 ### Here are the results!
 
![result1](https://github.com/fadh1l/style-transfer-vgg19/blob/main/result_1.png)


The art style has started to show up, but its not really a good result.
Initially the structures seemed to be not preserved, so I just tweaked the parameter that controls the how much of the structures present in the content image should be present.
Changed it from 1e-2 all the way to 10

![result2](https://github.com/fadh1l/style-transfer-vgg19/blob/main/result_2.png)

Now this is a much more satisfying result.
