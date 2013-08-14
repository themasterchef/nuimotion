# NUIMotion

## Fork note

This is @bengfarrell's NUImotion addon, with some Windows-specific hacks I had to use to make node.js load the module on Windows. At this time they work on my system, but I am still investigating if they will work on other systems (and indeed why these hacks are necessary).

## "NuiMotion" AddOn for Node.js

This AddOn serves as a wrapper for OpenNI and NITE.  OpenNI is an open source solution for any OpenNI compliant 3D sensor. Sensors include depth cameras like the Primesense Carmine, Asus Xtion, and Microsoft Kinect (if on Windows)  Meanwhile, NITE is the middleware for working with these devices.  It acts like the brain to capture skeletal, hand, gesture, etc data pulled from the depth information that OpenNI provides.

You can find the OpenNI foundation at www.openni.org

To get started, checkout the NuiMotion Wiki:

[https://github.com/bengfarrell/nuimotion/wiki](https://github.com/bengfarrell/nuimotion/wiki)

The wiki covers system requirements, installation, building, and basic usage/documentation.
