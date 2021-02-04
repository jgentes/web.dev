---
layout: post
title: Conclusion
authors:
  - thomassteiner
date: 2021-01-25
# updated: 2021-01-25
description: |
  This chapter provides a conclusion of the mini apps collection.
tags:
  - mini-apps
---

## Where does this leave us?

Writing and researching mini apps has been quite a ride, but one that I do not regret. On the one
hand, the success and the popularity of mini apps seems to have proven them right. On the other
hand, though, this success is geographically concentrated in regions where the few popular super
apps are dominant, at least at the time of writing. What is undoubtedly true is that the ecosystem
is highly fascinating and well worth a look. This collection of articles has provided deep-dives
into many of the aspects that make a difference when using and creating mini apps. From the
[DevTools](/mini-app-devtools/) experience to the
[mark-up](/mini-app-markup-styling-and-scripting/#markup-languages),
[styling](/mini-app-markup-styling-and-scripting/#styling), and
[scripting](/mini-app-markup-styling-and-scripting/#scripting) approaches, over to the
[component model](/mini-app-components/), and finally to the overall
[architecture](/project-structure-lifecycle-and-bundling/); mini apps provide learning and
inspiration opportunities for app developers, and even so for those who purely aim for the web.

My initial experiments with
[building a web application the mini app way](/an-example-project/) were
successful. Future work will show to what extent this model is performant and flexible enough to
cater for the many shapes that web apps can take. My current _ad-hoc_ approach can be formalized by
packaging up the relevant pieces of code in a dedicated library, `mini-app.js` if you will. What is
interesting is that this kind of programming goes back all the way to `frameset`. Just that today it
is about applications and not documents.

I see great potential for improvement with the entire web development experience by taking
inspiration from the various mini apps DevTools. From the easy
[(remote) on-device testing feature](/mini-app-devtools/#simulator-and-real-device-testing-and-debugging)
to the packaging and [building](/project-structure-lifecycle-and-bundling/#the-build-process)
experience; the integration of the [IDE](/mini-app-devtools/#mini-app-ides) with the DevTools
environment offers a lot of starting points for making developers' lives easier.

## Closing thoughts

From a features point of view, the web is catching up with mini apps. The ever-growing
[list of capabilities](/fugu-status/) makes use cases possible on the web that were unthinkable a
mere year ago. At the same time, the need for
[mini apps standardization](/mini-app-standardization/) shows that developers are not willing or
able to build the same mini app for each super app. On the horizon maybe there is a desire for an
abstraction layer on the browser level that allows for mini apps to run on the web, while noting that
the web is not immune from fragmentation, especially when looking at different browser vendors and
what they choose to implement and what not. Concluding, I am looking forward to seeing where all
this is headed. Thinking outside of the box and taking input and inspiration from outside of one's
own bubble can definitely help when building a better future on the web.

{% Banner 'neutral' %}
  👉 Congratulations, you have reached the end of the [mini apps collection](/mini-apps/).
{% endBanner %}