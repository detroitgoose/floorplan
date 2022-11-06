# floorplan

Hi, This is a stripped down version of my Home Assistant floorplan

This has been been heavily inspired/forked from https://github.com/lukevink/hass-config-lajv

This most important config steps are for the RGBW and RGB lights:

For color channels you'll need to render the light image in RED to accurately hue-color-shift
For rgb white (ie 255/255/255) you'll want to render with a COOL light for the blue-ish effect
For the white channel on an RGBW you'll want to render a third image with WARM light

Cheers!
