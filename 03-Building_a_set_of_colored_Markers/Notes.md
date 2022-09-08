-> Ath lesson 4
---->   utf-8 is a universal character set that includes almost every character from all human languages.

-> At lesson 21
---->   There are two main color models: The additive RGB(red, green, blue) model used in electronic devices, and the subtractive CMYK (cyan, magenta, yellow, black)model used in print.

-> At lesson 31
---->   Tertiary colors are created by combining a primary with a nearby secondary color.

-> At lesson 37
---->   Notice that the red and cyan colors are very bright right next to each other. This contrast can be distracting if it's overused on a website, and can make text hard to read if it's placed on a complementary-colored background.

It's better practice to choose one color as the dominant color, and use its complementary color as an accent to bring attention to certain content on the page.


-> At lesson 39
Notice how your eyes are naturally drawn to the red color in the center? When designing a site, you can use this effect to draw attention to important headings, buttons, or links.

There are several other important color combinations outside of complementary colors, but you'll learn those a bit later.

->At lesson 46
---->   A very common way to apply color to an element with CSS is with hexadecimal or hex values. While hex values sound complicated, they're really just another form of RGB values.

Hex color values start with a # character and take six characters from 0-9 and A-F. The first pair of characters represent red, the second pair represent green, and the third pair represent blue. For example, #4B5320.

-> At lesson 48
---->   The HSL color model, or hue, saturation, and lightness, is another way to represent colors.

The CSS hsl function accepts 3 values: a number from 0 to 360 for hue, a percentage from 0 to 100 for saturation, and a percentage from 0 to 100 for lightness.

If you imagine a color wheel, the hue red is at 0 degrees, green is at 120 degrees, and blue is at 240 degrees.

Saturation is the intensity of a color from 0%, or gray, to 100% for pure color.

Lightness is how bright a color appears, from 0%, or complete black, to 100%, complete white, with 50% being neutral.

-> At lesson 49
---->   You've learned a few ways to set flat colors in CSS, but you can also use a color transition, or gradient, on an element.

A gradient is when one color transitions into another. The CSS linear-gradient function lets you control the direction of the transition along a line, and which colors are used.

One thing to remember is that the linear-gradient function actually creates an image element, and is usually paired with the background property which can accept an image as a value.

-> At lesson 54
---->   Color-stops allow you to fine-tune where colors are placed along the gradient line. They are a length unit like px or percentages that follow a color in the linear-gradient function.

For example, in this red-black gradient, the transition from red to black takes place at the 90% point along the gradient line, so red takes up most of the available space:

linear-gradient(90deg, red 90%, black);

-> At lesson 64
---->   Even without the color-stops, you might have noticed that the colors for the green marker transition at the same points as the red marker. The first color is at the start (0%), the second is in the middle (50%), and the last is at the end (100%) of the gradient line.

The linear-gradient function automatically calculates these values for you, and places colors evenly along the gradient line by default.

-> At lesson 73
---->   Opacity describes how opaque, or non-transparent, something is. For example, a solid wall is opaque, and no light can pass through. But a drinking glass is much more transparent, and you can see through the glass to the other side.

With the CSS opacity property, you can control how opaque or transparent an element is. With the value 0, or 0%, the element will be completely transparent, and at 1.0, or 100%, the element will be completely opaque like it is by default.

-> At lesson 88
---->   Notice that the edges of the shadow are sharp. This is because there is an optional blurRadius value for the box-shadow property:

box-shadow: offsetX offsetY blurRadius color;

If a blurRadius value isn't included, it defaults to 0 and produces sharp edges. The higher the value of blurRadius, the greater the blurring effect is.

-> At lesson 89
---->   But what if you wanted to expand the shadow out further? You can do that with the optional spreadRadius value:

box-shadow: offsetX offsetY blurRadius spreadRadius color;

Like blurRadius, spreadRadius defaults to 0 if it isn't included.
