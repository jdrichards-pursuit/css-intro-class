# NOTES ABOUT CSS

3 different types of CSS

- inline CSS - you add CSS directly to an HTML element on the page
- internal CSS - use a style tag in your head tag and you include your styling
- external CSS - separate file, most useful way to style HTML and you can apply it to multiple pages instead of everything applying to one page or element.

Order of preference: External, Internal, Inline
Cascading Order: Inline, Internal, External

Workflow: Inline first just to see if it all works. If it works, then you abstract that code into external page.

COLORS IN CSS
AT LEAST 4 WAYS TO DEFINE COLORS

1. Use the default color name, this is not suggested;
2. rgb(a) - red, green, blue optional a for alpha. You choose colors based on a range between 0 and 255 for each color and it creates your hue
   rgb(123, 245, 255, 0.3) like old tvs
3. hexadecimal - hex for short
   #FFE4C4 numbers will count from 0-9, A=10, B=11, C=12....F=15
4. hsl - hue, saturation and light works in percentages
