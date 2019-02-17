# Google Map App Exercise

## Overview

This exercise is meant to flex your ability to work with a third party API, negotiate multi-step, async business logic.

The Google Maps API is famously not very intuitive. The docs aren’t going to give all the answers at a glance. You’ll have to be resourceful, piecing things together, and probably cross referencing with threads from Stack Overflow and the like.

## Guidelines

The guidelines are somewhat vague, allowing for a certain amount interpretation in how you implement, especially UX. Sometimes all those details are spelled out, and come with detailed Photoshop or Sketch designs illustrating use cases and functionality, but frequently you must rely on your own intuition on how it _should_ work

I recommend using [CodeSandbox - Vanilla](https://codesandbox.io/s/jl4n547kw9) since it’s a REPL, that provides a high functioning dev environment out of the box.

CodeSandbox allows you to install and use NPM packages, which you should feel free to do if you want with the exception of google maps specific tools.

Of course, feel free to reach out with questions. I'll conclude these guidelines with a programming maxim I've always thought was helpful:

> Get it working, get it right, get it fast

---

## Instructions

### Phase 1: Basic Map

1. Get a Google Map to render with a marker
2. Fix console warning by getting API key through Google Developer Console

### Phase 2: Markers with Tooltip

1. Put multiple markers on the map + get the map to center around it
2. Add the ability to click a marker and see details about it

### Phase 3: Location Search

1. Add text input to search for a location with autocomplete and update the map with selected location
2. Add ability to automatically resolve location through geolocation
3. Eject Google generated DOM elements, and use component API to get data.

### Phase 4: Find Closest Location

1. Generate an array of mock store locations, and add them as markers
2. Use the location search input to find which one is closest
3. Update the UI to indicate the closest store location
