---
layout: default
title: Open Artifacts 11ty Starter
eleventyNavigation:
  key: home
permalink: /index.html
---
{% from "macros/hero.njk" import hero %}
{% set options = {
  dark: false,
  titleText: "Evolutionary Design Group Manual",
  subtitleText: "A guide for creating your own group.",
  buttonText: "Read the Manual",
  buttonLink: "/cwc/project/about.html"
} %}
{{ hero(options) }}

{% section %}

## Welcome to the Evolutionary Design Group Manual

This is an Open Artifacts project with the goal of creating an operating manual of sorts around how to form, run and maintain an Evolutionary Design Group in your community.

Evolutionary Design Groups are a critical part of a system of change that I have variously called "Cultural Creation," "Evolutonary Design," "Evolving the World," or "Creating a World That Works for All Humanity." The system is described in my book {% externalLink "*Don't Save The World: Help Build a World That Will Save Us All*", "https://dontsavetheworld.com" %} and can be summarized like this:

- {% hilite "**The Worldview:**" %} Our ancestors designed and built the world we live in, hoping to help all humanity survive and thrive far into the future.
- {% hilite "**The Work:**" %} Those of us that choose to continue the work of our ancestors are **Cultural Creators**. In our hearts, we know that it is our turn to re-think the world gifted to us and to improve it.
- {% hilite "**The Process:**" %} As Cultural Creators, we engage in a **Creative Practice** that helps us strengthen our **Personal Universe** while improving the world.
- {% hilite "**The Platform:**" %} We collaborate with other Cultural Creators by creating, contributing to or adapting **Open Artifacts** projects which enable us to develop ideas and solve problems globally.
- {% hilite "**The Impact:**" %} We devote part of our Creative Practice to adapting and building Open Artifacts in our local community as members of self-directed **Evolutionary Design Groups**.

So, Evolutionary Design Groups are how life-sustaining tools, technologies, organizations and other cultural artifacts make their way into our everyday lives. With Evolutionary Design Groups working across the globe, we can affect positive change at a global scale.

{% endsection %}