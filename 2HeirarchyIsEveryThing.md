# COMMENT:: 8:40 to 9:35 (55 minutes)

## 2)Not all element are equal 
1. Visual hierarchy refers to how important the elements in an interface appear
in relation to one another, and it’s the most effective tool you have for
making something feel “designed”.
2. When you deliberately de-emphasize secondary and tertiary information,
and make an effort to highlight the elements that are most important, the
result is immediately more pleasing, even though the color scheme, font
choice, and layout haven’t changed:

## 2.2)Sizes is not everything
1. Relying too much on font size to control your hierarchy is a mistake — it
often leads to primary content that’s too large, and secondary content that’s too small.
1. Instead of leaving all of the heavy lifting to font size alone, try using font
weight or color to do the same job.
2. Try and stick to two or three colors:
• A dark color for primary content (like the headline of an article)
• A grey for secondary content (like the date an article was published)
• A lighter grey for tertiary content (maybe the copyright notice in a
footer)
3. Similarly, two font weights are usually enough for UI work:
• A normal font weight (400 or 500 depending on the font) for most text
• A heavier font weight (600 or 700) for text you want to emphasize
4. Stay away from font weights under 400 for UI work

## 2.3)Don’t use grey text on colored backgrounds
1. Choose a color with the same hue, and adjust the saturation and lightness
until it looks right to you:

## 2.4)Emphasize by de-emphasizing
1. giving the inactive items a softer color
so they sit more in the background:
2. For example, despite trying to make this active nav item “pop” by giving it a different color, it still doesn’t really stand out compared to the inactive items:


## 2.5)Labels are a last resort
1. that it makes it difficult to present the
data with any sort of hierarchy; every piece of data is given equal emphasis
2. For example, janedoe@example.com is an email address, (555) 765-4321 is a
phone number and $19.99 is a price.
3. For example, if you need to display inventory in an e-commerce interface,
instead of “In stock: 12”, try something like “12 left in stock”
4. If you’re building a real estate app, something like “Bedrooms: 3” could
simply become “3 bedrooms”.
5. When you’re able to combine labels and values into a single unit, it’s much easier to give each piece of data meaningful styling without sacrificing on clarity.

## 2.6)combine label with values. 
1. For example, if you need to display inventory in an e-commerce interface,
instead of “In stock: 12”, try something like “12 left in stock”.
2. If you’re building a real estate app, something like “Bedrooms: 3” could
simply become “3 bedrooms”.
3. lable are secondary => 
4. when to emphasize label 
   - This is often the case on information-dense pages, like the technical
specifications of a product.
   - If a user is trying to find out the dimensions of a smartphone, they’re
probably scanning the page for words like “depth”, not “7.6mm”.
5. Label are secondary => De-emphasize the label by making it smaller, reducing the contrast, using a lighter font weight, or some combination of all three.
6. When to emphasize a label=> This is often the case on information-dense pages, like the technical
specifications of a product.Don’t de-emphasize the data too much in these scenarios; it’s still important
information. Simply using a darker color for the label and a slightly lighter color for the value is often enough.



## 3)Separate visual hierarchy from document hierarchy
1. Using an h1 tag to add a title like Manage Account to a page makes perfect sense semantically, but because we’re trained to believe that h1 elements should be big, it’s easy to fall into the trap of making those titles bigger than they really need to be

# 4)Balance weight and contrast. 
1. The reason bold text feels emphasized compared to regular text is that bold
text covers more surface area — in the same amount of space, more pixels
are used for text than for the background.
2. Just like bold text, icons (especially solid ones) are generally pretty “heavy” and cover a lot of surface area. As a result, when you put an icon next to some text, the icon tends to feel emphasized.
3. A simple and effective way to do this is to lower the contrast of the icon by giving it a softer color.
4. This works anywhere you need to balance elements that have different
weights. Reducing the contrast works like a counterbalance, making heavier
elements feel lighter even though the weight hasn’t changed.

# 5)semantics are secondary 
1. Every action on a page sits somewhere in a pyramid of importance. Most
pages only have one true primary action, a couple of less important
secondary actions, and a few seldom used tertiary actions.

2. • Primary actions should be obvious. Solid, high contrast background
colors work great here.
Secondary actions should be clear but not prominent. Outline styles or
lower contrast background colors are great options.
• Tertiary actions should be discoverable but unobtrusive. Styling these
actions like links is usually the best approach.
3. If a destructive action isn’t the primary action on the page, it might be better
to give it a secondary or tertiary button treatment.

   


