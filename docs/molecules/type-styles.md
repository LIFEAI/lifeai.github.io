# Type Styles

life-ai-dsl-atom-font-smoothing

```css
html {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-shadow: 1px 1px 1px rgba(0,0,0,.004);
    -webkit-tap-highlight-color: rgba(0,0,0,0);
}
```



Life-ai-dsl-atom-font-stack

```scss
@mixin circular {
font-family: 'Circular Std Bold', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", “Segoe UI Emoji", "Segoe UI Symbol";
}
```

> Circular for both Marketing and Product brands. It is a strong but neutral typeface that lends personality to the page without overpowering the content.

[https://css-tricks.com/snippets/css/system-font-stack/](https://css-tricks.com/snippets/css/system-font-stack/)



##### Font size

Too many type sizes and styles at once can wreck any layout. A typographic scale has a limited set of type sizes that work well together along with the layout grid.



![https://storage.googleapis.com/material-design/publish/material_v_11/assets/0Bzhp5Z4wHba3alhXZ2pPWGk3Zjg/style_typography_styles_scale.png](https://storage.googleapis.com/material-design/publish/material_v_11/assets/0Bzhp5Z4wHba3alhXZ2pPWGk3Zjg/style_typography_styles_scale.png)



The basic set of styles are based on a typographic scale of 12, 14, 16, 20, and 34.



##### Font weights

```Css
font-weight: 300;
```

```Css
font-weight: 400;
```

```Css
font-weight: 700;
```

Font weight is another typographic style that can add emphasis and differentiate content in the hierarchy of the design. Font weight, in conjunction with type size, must be carefully balanced. At the same size, a bold weight will always have more emphasis than a lighter weight font. However, a larger, lighter weight font is ranked higher than a smaller, bold font.



##### Line Height

To achieve proper readability and appropriate pacing, line heights have been determined based on each style’s individual size and weight. Line wrapping only applies to Body, Subhead, Headline, and the smaller Display styles. All other styles should exist as single lines.

![https://storage.googleapis.com/material-design/publish/material_v_11/assets/0Bzhp5Z4wHba3Q1VaNVBsdFozUTg/style_typography_styles_lineheight1.png](https://storage.googleapis.com/material-design/publish/material_v_11/assets/0Bzhp5Z4wHba3Q1VaNVBsdFozUTg/style_typography_styles_lineheight1.png)



Pairing examples



![https://storage.googleapis.com/material-design/publish/material_v_11/assets/0Bzhp5Z4wHba3S0hlSFBQRVE0QlU/style_typography_styles_lineheight2.png](https://storage.googleapis.com/material-design/publish/material_v_11/assets/0Bzhp5Z4wHba3S0hlSFBQRVE0QlU/style_typography_styles_lineheight2.png)



life-ai-dsl-atom-standard-line-height

```css
line-height: 1.5;
```

life-ai-dsl-atom-heading-line-height

```css
line-height: 1.25;
```

> Line-height, traditionally known as leading, is one of several factors that directly contribute to readability and pacing of copy. Line-heights are based on the size of the font itself. Ideal line-heights for standard copy have a ratio of 1.5. For example, a type at 1em/16px would have a line-height of 24px (16 x 1.5). The exception to this rule are headings, which need less spacing and therefore have a line-height ratio of 1.25.



##### Colors & contrast

A text color that is too similar to the background color is hard to read. Text with too much contrast can also be hard to read. This is especially true of light-colored text against dark backgrounds.

Text should maintain a minimum contrast ratio of at least 4.5:1 (calculated based on luminance values) for legibility. A ratio of 7:1 is preferred.

These color combinations also consider contrast ratios for users who perceive color differently.



![https://storage.googleapis.com/material-design/publish/material_v_11/assets/0Bzhp5Z4wHba3dGx2T1FqM0xXbTA/style_typography_styles_contrast.png](https://storage.googleapis.com/material-design/publish/material_v_11/assets/0Bzhp5Z4wHba3dGx2T1FqM0xXbTA/style_typography_styles_contrast.png)



##### Line breaking

Avoid leaving large gaps and orphans on a line. Try not to leave very short words such as prepositions at the end of a line. Well-considered line breaks can avoid hyphenation of words altogether.

![https://storage.googleapis.com/material-design/publish/material_v_11/assets/0Bzhp5Z4wHba3RDczVGtWcWNnc3c/style_typography_styles_linebreaks2.png](https://storage.googleapis.com/material-design/publish/material_v_11/assets/0Bzhp5Z4wHba3RDczVGtWcWNnc3c/style_typography_styles_linebreaks2.png)





life-ai-dsl-atom-line-length

General line-length = 52 - 78 characters

![https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsVDdtU1NfU3Jtdlk/style_typography_styles_linelengths1.png](https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsVDdtU1NfU3Jtdlk/style_typography_styles_linelengths1.png)



![https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsMzYxcGowWTE5NW8/style_typography_styles_linelengths2.png](https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsMzYxcGowWTE5NW8/style_typography_styles_linelengths2.png)

Consider this advice on readability and line length from the Baymard Institute:

“You should have around 60 characters per line if you want a good reading experience. Having the right amount of characters on each line is key to the readability of your text.”

"Too wide – if a line of text is too long, the user’s eye will have a hard time focusing on the text. This is because the length makes it difficult to get an idea of where the line starts and ends. Furthermore it can be difficult to continue from the correct line in large blocks of text.”

"Too narrow – if a line is too short, the eye will have to travel back too often, breaking the reader’s rhythm. Too short lines also tend to stress people, making them begin on the next line before finishing the current one (hence skipping potentially important words).”

Source: “Readability: the Optimal Line Length,”

[http://baymard.com/blog/line-length-readability](http://baymard.com/blog/line-length-readability)



life-ai-dsl-atom-letter-spacing

```css
Letter-spacing: 0.5px
```



