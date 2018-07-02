---
layout: post
title: iPhone X Support
---
The iPhone X has been out for nearly 9 months now, yet there are still a handful of apps installed on my phone that
don't run in full screen, "embracing the notch".  Generally, every time I launch one of them, I'm kind of surprised. And,
I'm a developer. I know it's not as easy as you might think.  So, I thought I'd explain to non-developers why this might happen.

## In One Sense, It's Easy
All an iOS developer needs to do to get iPhone X support in their app is compile for iOS 11. Seriously, that's it. After
that, the app will run full screen on the device.

## In Another, It's Hard
Back in the good ol' days of iPhone development, there was one screen size.  Phones were 320x480 pixels, and that was the only
size you ever needed to worry about.  In 2010, we got the first iPad, with its fancy 1024x768 resolution. If it ran a phone app, it
would scale it to the usual 320x480 resolution. When the iPhone 4 with the first retina display came out, there wasn't so much
a resolution change, as a "quality of graphics" change.  We stopped thinking in terms of "pixels" and though it terms of "points",
which is really just an interesting way for Apple to say "it's 320x480, and if it's on a retina display, we'll use higher quality
graphics if you supply them".  At that point, we all scrambled to redo our apps with higher quality images so they would look nice
on retina.

After that, things got a little crazy for us ... the iPhone 5 was taller at 320x568. With iPhone 6, the iPhone got wider and
taller: 375x667. Then, along came the plus-size devices: 414x736.  iPads started coming in different resoutions. Finally, the
iPhone X is a whopping 812 points tall, while retaining the 375 width.

Why does this matter?  Because we need to make sure things look good in all of these different configurations, and that's not always
easy. Here's an example from my upcoming app [Keep the Count]. This is the iPhone 6, which is effectively my baseline as
I design these screens.  

<img src="{{ '/assets/postimages/20180624_screen0.png' | relative_url }}" class="screenshot"/>

Now, look what happens when it shrinks down to 320x480 on an iPad (running in "iPhone mode"). And, on the right, the same
screen on the freakishly tall iPhone X.

<img src="{{ '/assets/postimages/20180624_screen1.png' | relative_url }}" class="screenshot"/>
<img src="{{ '/assets/postimages/20180624_screen2.png' | relative_url }}" class="screenshot"/>

In terms of vertical space, the iPhone X has nearly twice what's available to the version on the iPad.  Look at all that space! And
the iPad version doesn't really have enough room for all the design elements. Notice the reset button is chopped off. What's a developer to do?

## It takes work
Obviously, there are ways to deal with this. On iPad, I'll shrink some things. On iPhone X, I'll find interesting ways to take up the
space.  That's not the point.  The point is, those changes aren't _automatic_.  As a developer, I need to evaluate how my app
looks on all devices, decide how to deal with aberrations, then write code to do it.

It's great that Apple gives us, as consumers, all these choices for different screen sizes to suit every purpose. But, there is
a cost to the developer, and it means it'll take time to deal with each new and unique screen configuration.

So, next time you're wondering "why doesn't this app support iPhone X yet?" ... now you know.

When it's released (soon, I promise!), I hope you'll check out [Keep the Count]. I'll look good, no matter which size iPhone you have.

[Keep the Count]: /apps/keepcount
