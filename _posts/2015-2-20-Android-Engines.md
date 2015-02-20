---
layout: post
title: Comparison of Android 2D Engines
---

## Objective
Research about different 2D game engines for Android.

## Conclusion
All three compared engines seem to have all the features we need. They each feel pretty similar. Box2D seems to have the most features and support, however it is written in C++. JBox2D is the Java port of Box2D which supports many of the same features of Box2D. JBox2D does not appear to have as much maintenance support as Box2D, which is not necessarily a deal breaker but should be kept in mind. JGame contains a patched version of JBox2D which means it would support most, if not all, the same features as JBox2D. However JGame seems to have the littlest amount of support from the developer. This can be seen by trying to view the tutorials, which are all broken links.

All three of these engines are open source, so we would not have to worry about obtaining licenses. Box2D is the most robust and supported of the three. Box2D and JBox2D seem to be the best choices, the main decision here would be whether we want to use Java or C++ to develop. I would be more inclined toward using Java, as it is Android's native language and is easier to use than C++.

## Engines Compared

*	[JGame](http://www.13thmonkey.org/~boris/jgame/)
*	[Box2D](http://box2d.org/about/)
*	[JBox2D](http://www.jbox2d.org/)

## Engine Comparison
### JGame

Features
*	Platforms
**	JRE 1.3+
**	J2ME mobile
**	Android 2.1+
*	Flash Actionscript 3
*	Sprites with automatic animation and collision detection
*	Tile-based background
*	Programmed at a fixed resolutions, but scalable to any resolution
*	Has a patched version of JBox2D physics engine

### Box2D

Features
*	Continuous collision detection
*	Convex polygons and circles
*	Collision groups and categories
*	Continuous physics with time of impact solver
*	Contact, friction, and restitution
*	Stable stacking
*	Momentum decoupled position correction
*	Small block and stack allocators
*	Portable C++ with no use of STL containers

### JBox2D

Java version of Box2D

Features
*	Rigid body physics
*	Stable stacking
*	Gravity
*	Persistent contact solver
*	Boxes, circles, edges and polygons
*	Continuous collision detection
*	Sensors
*	Dynamic, kinematic, and static bodies