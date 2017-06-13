# Metrics and Keylines

Baseline grid

`8dp`

Iconography in toolbars align to a `4dp` square baseline grid.

Type aligns to 

`4dp`

##### Ratio Keylines

The proportion of an element’s width to its height (called the **aspect ratio**) applies to both UI elements and screen size. It is written as width:height.

Aspect ratios are recommended:

16:9 (56.25%) 

3:2 (66.6666%)

4:3 (75%)

1:1 (100%)

3:4

2:3

![https://storage.googleapis.com/material-design/publish/material_v_11/assets/0Bx4BSt6jniD7ZjBCVzdPOENpT28/layout_metrics_ratiokeylines1.png](https://storage.googleapis.com/material-design/publish/material_v_11/assets/0Bx4BSt6jniD7ZjBCVzdPOENpT28/layout_metrics_ratiokeylines1.png)



**For example:**

- A 1:1 aspect ratio means an element has equal height and width.
- A 360dp wide image with a 2:3 aspect ratio has a height of 540. 

Determine the width or height of your element for a chosen aspect ratio using the below formulas. The aspect ratio is always expressed as a fraction. For example, 3:2 is treated as 3/2.

Width = Aspect ratio * Height 

Height = Width/Aspect ratio



**Maintaining aspect ratios with css**

bottom/top padding

- 1:1 ≙ 100%
- 1:2 ≙ 200%
- 2:1 ≙ 50%
- 3:2 ≙ 66.6666%
- 4:3 ≙ 75%;
- 16:9 ≙ 56.25%
- 21:9 ≙ 42.8571%



##### Touch target size

To ensure balanced information density and usability, touch targets should be at least 48 x 48 dp. In most cases, there should be 8dp or more space between them.

Size elements at least 48dp high and wide to ensure a physical size of about 9mm regardless of screen size. The recommended target size for touchscreen objects is 7-10mm.