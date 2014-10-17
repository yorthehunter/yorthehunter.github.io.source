---
layout: post
title:  "Mobile Minded, Not Mobile First"
categories: mobile
rgb: "239, 228, 208"
textcolor: "#444"
bgimage: "bg-design-min-05.svg"
---

I work on a lot of internal applications. These are often web applications that service and manage our warehouse operations. I’m very lucky because I have much greater control over the environment our users are using: operating system, screen resolution, web browser, and so on. Even if when I don't directly control these elements, at least I have foresight when it comes time to begin designing and implementing a new product.

This is more than I can say for most designers-at-large. Not only do we typically struggle with browser compatibility (I thought the browser wars were over!), web fonts, ever-evolving front-end technologies, pixel densities, kerning, leading, device requirements, and viewport sizes, but all of these are expected to work wonderfully on all devices at all times—especially in e-commerce.

In our desperation, we’ve espoused “Mobile First” to account for our need to service the iPhone-weilding maniacs we’ve created. The short story is this: it’s easier to gorge ourselves on the conveniences of the world from our palm devices, leaving us a free hand to hold a cheesesteak, toilet bowl plunger, or miniature American flag. But that’s ok; if I can order a subscription service for wine while I’m in the toilet, then the world really isn’t a bad place.

But what then of those buying new iPads of varying sizes bimonthly, or those monsters who choose to browse the web from their phones in landscape mode, or those Mountain Dew fueled gamers on their 40” dual-screens? There’s two obvious design paths we can consider: start with desktop and scale down or start with mobile and scale up. [Here’s an appropriately cynical post](http://designshack.net/articles/css/mobilefirst/) that refers to these as "Graceful Degradation” and "Progressive Enhancement,” respectively. This is pretty representative of the mind of a designer as he or she considers a new project (unless you’re designing a government website. Then, your only option is to support IE6 at 800x600, 256 color resolution).

But how about this: *start with the basic needs of your user and scale outward*. We don’t pretend to know the best user experience without first trying to understand our users needs, so why would we pretend to know the best design process without knowing who our users are? In this way, we can define our users' needs, while keeping enhancement and degradation in our subconscious.

If we know that 90% of our users—those “converting” on our web application—are on last year’s chrome books, then we have an immediate idea of what kind of canvas on which we have to paint. Yes, it will be nice in six months to offer the same experience from a watch, but until then, we work with what’s in front of us. If we’re as savvy as we say we are, we’ll be well in the loop when it comes time to scale down (or up) to accommodate the latest palm pilot (or five monitors at once). If we’re clever, we can put a responsive grid in place, typography that uses math to scale dynamically, or responsive images with very little effort now to accommodate a wider range of like users.

During all of this, we remain mobile minded, but we know that our product first-and-foremost meets the needs of the most vital. If your prerogative is to design for every device and resolution beforehand, you’re missing out on presenting a great product to your known users and getting that crucial first round of feedback early.

But like I said, I’m very lucky. I am afforded the conveniences of knowing whom our users are and how they use our system. Joe Freelancer would need to dig a little further, but I’m sure the answers are out there.