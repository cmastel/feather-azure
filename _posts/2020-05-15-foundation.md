---
layout: post
title:  "Foundation"
categories: thoughts
---

> The status quo isn't worth protecting. It's so easy to be in reaction, on the defensive, fighting for the world we had yesterday. Fight for something better, something we haven't seen yet, something we have to invent.
>
> -- Jen Pahlka

The emerging norm for web development is to build a React single-page application, with server rendering. The two key elements of this architecture are something like:

    The main UI is built & updated in JavaScript using React or something similar.
    The backend is an API that that application makes requests against.

This idea has really swept the internet. It started with a few major popular websites and has crept into corners like marketing sites and blogs.

I’m increasingly skeptical of it.

There is a sweet spot of React: in moderately interactive interfaces. Complex forms that require immediate feedback, UIs that need to move around and react instantly. That’s where it excels. I helped build the editors in Mapbox Studio and Observable and for the most part, React was a great choice.

But there’s a lot on either side of that sweet spot.