---
layout: post
title: '"This app should be free"'
---
There's a general sentiment among a lot of iPhone users that small, single-purpose apps should be free.
Companies like Google and Facebook help perpetuate this line of thought, because they crank out a ton of
quality, feature rich-apps and don't charge for them. But, those guys are rich and they don't need app sales.

Let me explain why apps from small developers (like Fingers Akimbo) can't be free.

### Development equipment costs money

Writing an iOS app requires, at minimum, a Mac. You can get a bare bones [Mac Mini][mini] for $500,
but it's not going to have the horsepower you need in order to do development.
What you really need for development is on the order of a $3000 iMac or MacBook Pro.
And you need a new one every 2-3 years, to keep up to date.

You also really need to test your code on an actual device, and not rely on an iPhone/iPad simulator.
That means, you need at least one iPhone and/or iPad, depending on what you target for your app.

One computer + one iOS device is bare minimum ... most of the time, you want to test on a small device
(like an iPhone SE), a large device (like an iPhone 8 Plus), and an iPad.
Throw in whatever wildcard new technology Apple just released (like an iPhone X, with the "safe area")
and you're racking up quite the hardware bill, just to ensure that when someone with that type of
device runs your app, it runs properly.

### Developer tools cost money

The primary tool for an iOS developer is Xcode, which is available [for free][adp]
from Apple.  But, to be truly productive, you need a few other things. For example, [Reveal]
is an excellent debugging tool to help you find out where your display code is going astray.
[Sketch] is invaluable for designing screens.
If you're anything like me, your drawing skills are pretty crappy, so you need [someone][glyphish]
[else][thenounproject] to do icons/graphics, and there's usually a fee attached.  
These are just a few examples.

### The store costs money
Apple may give away Xcode, but that's only for _writing_ apps. If you want to offer them to other people,
it costs $99/year just for [the right to][adp] put apps on the store -- whether you offer them for free or not. So,
even if you magically have the hardware and development software for free, it costs $99 _per year_
just to "sell" free apps.

### Time is money
Developers put time and effort into making apps, and should be compensated.
We have bills. I don't mean the stuff above. We need to pay for food and shelter, just like everyone else.
Transportation. Medicine and insurance. All the stuff you pay for monthly, we have to pay for somehow too.
Selling software is how we do it.

## Just show me ads
When I started Fingers Akimbo, my first app was done by acquiring the rights to 
[Points] from [BigSprocket], then rewriting it and modernizing it.
Whereas [BigSprocket] sold the app for a buck, I thought I'd offer it for free, and support it via ads. 
That way, you get the app for free, and I still get paid. If you download the app now, 
there is an ad banner at the bottom, and there is IAP to turn off those ads.

To date, here's how much I have earned from ads, and the IAP to turn them off.

Drumroll, please .... *$0*.

Easy Street, here I come, right? The sad reality is that it takes a ridiculously large number of 
impressions before you see any money from ads. A niche app like [Points] just isn't in front of enough 
eyeballs to even earn $1/year with ads. Not even a buck. The people making
money on ads are content consumers (Facebook, newspapers, etc) and games.

From a technical perspective, including an ad framework in the app causes unnecessary bloat 
and code churn, too. They include a _ton_ of extra frameworks, and they are constantly releasing 
new versions, expecting us to change our code to meet their requirements.
I'm sure it's tiring for the people actually making money on ads. For people making zero, it's maddening.

## So ... now what?

Well... if you have an app need (such as [tracking your HR points and absences][points]), you should be 
willing to pay someone to write it for you. In general, small apps cost a buck or two, and that's entirely fair.  
If you aren't willing to part with $1 for software, but think nothing of throwing money at Starbucks, 
please re-read the top of this post. Little guys like my aren't trying to get rich, we're trying not to go 
broke from operating expenses.

If that still doesn't convince you, ok. I guess the app isn't good enough. 
Email the developer and tell them what the app needs added in order to earn your business. 
My email address is at the bottom of the page, and I'd love to hear your feedback on all things
Fingers Akimbo.

### And?

Well, I'm sure you figured out by now ... [Points] isn't going to be free for much longer.
There's an update coming out shortly, to support iPhone X. With that release, the ads will come out, 
and the price goes to a buck. Existing users will simply convert to paid users, no money required. 
That's a thank you for being early adopters (or converters from BigSprocket's equivalent app). 
New users will pay (the more than fair price of) $0.99.

Future apps, such as [Keep the Count] will also be paid apps.

[reveal]: https://revealapp.com
[sketch]: https://sketchapp.com
[thenounproject]: https://thenounproject.com
[glyphish]: http://glyphish.com
[adp]: https://developer.apple.com/account/
[mailme]: mailto:hello@fingersakimbo.com
[BigSprocket]: https://bigsprocket.com
[points]: /apps/points
[Keep the Count]: /apps/keepcount
[mini]: https://www.apple.com/mac-mini/
