# layoutim
A more powerful png thumbnailer

## Motivation
I often use imagemagick and I wanted to lay out png images
on a grid, so I used its montage command.

However it puts in these borders which are fine with 4, 9 images but if you want
a more images, the border starts to dominate.

How about working out the options for skipping the border? Excavate documentation? No thanks!
I had done similar things in the past and hit upon old code using libgd.
That's the one! libgd will do it for you with much ore control.

In fairness, imagemagick has an api, but I was too familiar with libgd
to bother starting on it.

In any case, libgd uses libpng behind it, so it'snot reinventing the wheel
to do it this way.
