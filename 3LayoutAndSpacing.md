COMMENT:: 9:40 to 10:09

#  3.1)Start with too much whiteSpace. 
1. One of the easiest ways to clean up a design is to simply give every element a little more room to breathe.
2. A better approach is to start by giving something way too much space, then remove it until you’re happy with the result
  

# 3.2) Establish a spacing and sizing. 
# 3.3)Linear scale won't work 
1.  something like
“make sure everything is a multiple of 4px” — a naive approach like that
2. At the small end of the scale (like the size of an icon, or the padding inside a button), a couple of pixels can make a big difference. Jumping from 12px to 16px is an increase of 33%!
3. If you want your system to make sizing decisions easy, make sure no two
values in your scale are ever closer than about 25%.
   
# 3.3)You don't need to fill whole screen.
1. If you only need 600px, use 600px. Spreading things out or making things
unnecessarily wide just makes an interface harder to interpret, while a little extra space around the edges never hurt anyone.

2. Sink to canvas=> make design fit for 600px 
3. If you wanted to make better use of the available space without making the form harder to use, you could break the supporting text out into a separate column:

4. Whenever you’re relying on spacing to connect a group of elements, always
make sure there’s more space around the group than there is within it —
interfaces that are hard to understand always look worse.  

## 3.4)Grids are overrated. 
1. For example, consider a traditional sidebar layout. Using a 12-column grid system, you might give the sidebar a width of three columns (25%) and the main content area a width of nine columns (75%).If you make the screen wider the sidebar gets wider too, taking up space
that could’ve been put to better use by the main content area.
2. In this situation, it makes much more sense to give the sidebar a fixed width
that’s optimized for its contents. The main content area can then flex to fill
the remaining space, using its own internal grid to lay out its children.
3. Instead of sizing elements like this based on a grid, give them a max-width
so they don’t get too large, and only force them to shrink when the screen
gets smaller than that max-width.    

## Relative sizing doesn't scale
1. For example, say you’re designing an article at a large screen size. If your
body copy is 18px and your headlines are 45px, it’s tempting to encode that
relationship by defining your headline size as 2.5em; 2.5 times the current
font size.
2. Say you reduce the size of your body copy to 14px on small screens to keep
the line length in check. Keeping your headlines at 2.5em means a rendered
font size of 35px — way too big for a small screen!
3. A better headline size for small screens might be somewhere between 20px
and 24px:
4. the difference between
small elements and large elements should be less extreme at small screen
sizes.
5. **Relationship within elements**=> 
   -   Compare that to these buttons, where the padding gets more generous at
larger sizes and disproportionately tighter at smaller sizes:
  - Let go of the idea that everything needs to scale proportionately — giving
yourself the freedom to fine-tune things independently makes it a hell of a
lot easier to design for multiple contexts

6. **Avoid ambiguous spacing**
- horizontal and vertical spacing resolves. 
