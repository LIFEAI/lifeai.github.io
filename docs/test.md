# Getting Started
- Designers
- Developers
# Guidelines
- Content
  - Conversation
- Motion
- Principles
- Branding
  - Voice and Tone
  - Press Kit
- Framework/Structure
# Atoms
#### Metrics and Keylines 
Baseline grid 8px
Type align to 4 px
Leading div by 4
Ratio Keylines
get from material design documentation
#### Grid
life-ai-dsl-atom-grid-xs
`TBD`
life-ai-dsl-atom-grid-s
`TBD`
life-ai-dsl-atom-grid-m
`TBD`
life-ai-dsl-atom-grid-l
#### Color
`#000000`
life-ai-dsl-atom-ui-color
`#000000`
life-ai-dsl-atom-ui-text-color
`#000000`
life-ai-dsl-atom-text-color
`#000000`
#### Typeface
life-ai-dsl-atom-typography
```scss
@mixin circular {
font-family: 'Circular Std Bold', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", “Segoe UI Emoji", "Segoe UI Symbol";
}
```
> Circular for both Marketing and Product brands. It is a strong but neutral typeface that lends personality to the page without overpowering the content.
[https://css-tricks.com/snippets/css/system-font-stack/](https://css-tricks.com/snippets/css/system-font-stack/)
##### Type Scale 1.125
##### Font size
`TBD`
##### Type Scale 1.125
16 base
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
> Font weight is another typographic style that can add emphasis and differentiate content in the hierarchy of the design. Font weight, in conjunction with type size, must be carefully balanced. At the same size, a bold weight will always have more emphasis than a lighter weight font. However, a larger, lighter weight font is ranked higher than a smaller, bold font.
##### Line Height
life-ai-dsl-atom-standard-line-height
```css
line-height: 1.5;
```
life-ai-dsl-atom-heading-line-height
```css
line-height: 1.25;
```
> Line-height, traditionally known as leading, is one of several factors that directly contribute to readability and pacing of copy. Line-heights are based on the size of the font itself. Ideal line-heights for standard copy have a ratio of 1.5. For example, a type at 1em/16px would have a line-height of 24px (16 x 1.5). The exception to this rule are headings, which need less spacing and therefore have a line-height ratio of 1.25.
life-ai-dsl-atom-line-length
**Line-length: 52 - 78 characters**
life-ai-dsl-atom-letter-spacing
```css
Letter-spacing: 0.5px
```
life-ai-dsl-atom-font-smoothing
```css
html {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-shadow: 1px 1px 1px rgba(0,0,0,.004);
    -webkit-tap-highlight-color: rgba(0,0,0,0);
}
```
#### Images
life-ai-dsl-atom-image-avatar
  <img src="../src/assets/images/avatar.jpg" />
```html
<span class="slds-avatar slds-avatar--medium">
  <img src="/assets/images/avatar2.jpg" alt="company name" />
</span>
```
life-ai-dsl-atom-image-avatar-brand
  <img src="../src/assets/images/avatar-brand.jpg" />
```html
<span class="slds-avatar slds-avatar--medium">
  <img src="/assets/images/avatar2.jpg" alt="company name" />
</span>
```
life-ai-dsl-atom-image-logo
  <img src="../src/assets/images/logo.jpg" />
```html
<span class="slds-avatar slds-logo--medium">
  <img src="/assets/images/avatar2.jpg" alt="company name" />
</span>
```
life-ai-dsl-atom-image-card
life-ai-dsl-atom-border-radius
2 or 4
life-ai-dsl-atom-border-width
1px
life-ai-dsl-atom-motion
`TBD`
Material design documentation
## Molecules
Follow material
life-ai-dsl-molecule-typography-h1
life-ai-dsl-molecule-typography-h2
life-ai-dsl-molecule-typography-h3
life-ai-dsl-molecule-typography-h4
life-ai-dsl-molecule-typography-h5
life-ai-dsl-molecule-typography-h6
life-ai-dsl-molecule-typography-title
life-ai-dsl-molecule-typography-paragraph
life-ai-dsl-molecule-typography-body
life-ai-dsl-molecule-typography-bodysmall
Life-ai-dsl-molecule-typography-message
life-ai-dsl-molecule-button-primary
life-ai-dsl-molecule-button-primary-disabled
life-ai-dsl-molecule-button-primary-icon
life-ai-dsl-molecule-button-secondary
life-ai-dsl-molecule-button-secondary-dsabled
life-ai-dsl-molecule-button-secondary-icon
life-ai-dsl-molecule-card
## Cells
life-ai-dsl-cell-card
life-ai-dsl-cell-modal
life-ai-dsl-cell-notification
life-ai-dsl-cell-prompt
life-ai-dsl-cell-select
life-ai-dsl-cell-text-message
life-ai-dsl-cell-slider
## Organisms
life-ai-dsl-organism-card-message-slider
life-ai-dsl-organism-card-message
life-ai-dsl-organism-card-location
# Component Status
Hi my name is life AI
How can I help you?
Response
Slider