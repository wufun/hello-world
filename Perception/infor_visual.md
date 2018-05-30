# Depth Cues:
**I. Monocular Static (pictorial)**
1. Linear perspective
2. Texture gradient
3. Size gradient
4. Occlusion
5. Depth of focus
6. Shape-from-shading
7. Vertical position
8. Relative size to familiar objects
9. Cast shadows
10. Depth-from-eye accommodation (this is nonpictorial)
----
**II. Monocular dynamic (moving picture)**
1. Structure-from-motion (kinetic depth, motion parallax)
---
**III. Binocular**
1. Eye convergence
2. Stereoscopic depth

## Perspective Cues
- **Parallel lines** *converge* to a point.
- objects of **known size** have a powerful role in determining the size of **unkown** one.
- Texture elements become **smaller** with distance.

## Pictures Seen from the Wrong Viewpoint
- robustness of linear perspective
- FTVR: motion parallax
> With this information,
a 3D scene can be computed and viewed so the perspective is “correct” at all
times by adjusting the viewpoint parameters in the computer graphics software
(Deering, 1992). I called this setup fish-tank virtual reality to contrast it with the
immersive virtual reality that is obtained with head-mounted displays

## Occlusion
- If one object overlaps or occludes another, it appears closer to the observer

## Shading Models
1. Lambertian shading
2. Specular shading
3. Ambient shading
3. Cast shadows
> The kinds of complex shadows that result from multiple light
sources and radiosity modeling may be visually confusing rather than helpful.

## Cushion Maps
## Surface Texture
## Cast Shadows
- relative height of objects above a plane
- shadow motion

## Depth of Focus
> simulating depth of focus is an excellent way to highlight information
by blurring everything except that which is critical.

## Eye Accommodation
> The eye changes focus to bring attended objects into sharp focus on the retina. If the
brain could measure the eye’s accommodation this might be a depth cue.

## Structure-from-motion
1. motion parallax
> when we look sideways out of a
car or train window. Things nearby appear to be moving very rapidly, whereas objects
close to the horizon appear to move gradually.
2. kinetic depth effect
> by having the scene
rotate about a vertical axis. If the rotation is oscillatory, then the viewpoint can be
approximately preserved.

## Eye Convergence
## Stereoscopic Depth
> Stereoscopic displays
simulate these **differences** by presenting different images to the left and right eyes of
viewers. \
> If the **disparity** between the two images becomes too **great**, double vision (called **diplopia**)
occurs. \
> The 3D area within which objects can be
fused and seen without double images is called **Panum’s fusional area**

## Problems with Stereoscopic Displays
> Double-imaging problems tend to be
much worse in stereoscopic computer displays than in normal viewing of the 3D
environment.

## Frame Cancellation
## The Vergence-Focus Problem
## Distant Objects
- disparities too small
## Making Effective Stereoscopic Displays
- require high resolution
## Cyclopean Scale
- to deal with diplopia problems
- ![image](https://github.com/wufun/hello-world/blob/master/Perception/cyclopean%20scale.png)

## Virtual Eye Separation
> If the virtual eye separation is smaller
than the actual eye separation, stereo depth is decreased. If the virtual eye separation is
larger than the actual eye separation, stereo depth is increased.

## Artificial Spatial Cues
- consider using drop lines to add depth information for small numbers
of discrete isolated objects.
![image](https://github.com/wufun/hello-world/blob/master/Perception/artificial.png)
- consider using halos to enhance occlusion
where this is an important depth cue and where overlapping objects have the
same color or minimal luminance difference.

# Depth Cues in Combination
> cues
are combined with different weightings depending on the task. Whatever the task
(for example, threading a needle or running through a forest), certain depth cues are
informative and other cues can be irrelevant.
- There is a dependency graph for depth cues. Occlusion is the most basic depth cue.
