---
id: 5779
title: Computer Graphics Questions Part 8
date: 2015-11-17T21:58:00+00:00
author: chito
layout: post
guid: http://www.afriqueunique.org/2015/11/17/12097778/
permalink: /2015/11/17/computer-graphics-questions-part-8/
swp_pinterest_image_url:
  - ""
swp_cache_timestamp:
  - "419229"
view_num:
  - "1"
post_views_count:
  - "129"
bs_social_share_facebook:
  - "0"
bs_social_share_twitter:
  - "0"
bs_social_share_reddit:
  - "0"
bs_social_share_google_plus:
  - "0"
bs_social_share_linkedin:
  - "0"
bs_social_share_interval:
  - "1570918048"
categories:
  - LEARNING
---
<div>
  UNIT III
</div>

<div>
  1. Explain reflection and shear?
</div>

<div>
  Reflection
</div>

<div>
  • It is a mirror image of an object
</div>

<div>
  • Rotating about 180 degree
</div>

<div>
  • Flat object moving in the xy plane
</div>

<div>
  • Reflection about y axis flips x coordinates
</div>

<div>
  • Reflection point as pivot point is same as above
</div>

<div>
  • To obtain the transformation matrix for reflection diagonal
</div>

<div>
  is y = -x
</div>

<div>
  • Sequence
</div>

<div>
  • Clockwise rotation by 45 degree
</div>

<div>
  • Reflection about y axis
</div>

<div>
  • Counter wise rotation by 45 degree
</div>

<div>
  Shear
</div>

<div>
  • Internal layer cause to slide over each other called shear
</div>

<div>
  24
</div>

<div>
  • Transforms coordinate position as
</div>

<div>
  X ‘= x + shx . y’ , Y’ = y
</div>

<div>
  • Shift in the position of objects relative to shearing reference
</div>

<div>
  lines are equivalent to translations
</div>

<div>
  2. Explain Liang Barsky line clipping
</div>

<div>
  • Faster line clipper of the parametric equation of a line
</div>

<div>
  segment
</div>

<div>
  • Line parallel to one of the clipping boundaries
</div>

<div>
  • Line intersects the extension of boundary k
</div>

<div>
  • If u1 > u2 line is outside the clipping window
</div>

<div>
  • Else inside the clipping window
</div>

<div>
  • Clipping is done using the reflection in the clip window
</div>

<div>
  3. Explain Sutherland Hodgeman polygon clipping
</div>

<div>
  • Clipping polygon which lies inside the clipping window
</div>

<div>
  • Four possible cases
</div>

<div>
  • If the first vertex is outside the window
</div>

<div>
  boundary and the second vertex inside
</div>

<div>
  • If the first vertex is inside the window
</div>

<div>
  boundary and the second vertex outside
</div>

<div>
  • If both are outside
</div>

<div>
  • If both are inside
</div>

<div>
  • Repeat the process of algorithm
</div>

<div>
  • Convex polygon are correctly clipped using this clipping
</div>

<div>
  • Concave and convex polygon are also used
</div>

<div>
  4. Explain about clipping operations
</div>

<div>
  • Clip a picture from either outside or inside a region known
</div>

<div>
  as clipping
</div>

<div>
  • Also called as clipping algorithm
</div>

<div>
  • The region against the object is known as clip window
</div>

<div>
  • Clipping operations on different types of objects
</div>

<div>
  25
</div>

<div>
  • Point clipping
</div>

<div>
  • Polygon clipping
</div>

<div>
  • Area clipping
</div>

<div>
  • Line clipping
</div>

<div>
  • Curve clipping
</div>

<div>
  • Text clipping
</div>

<div>
  • Polygon and line clipping are the standard clipping
</div>

<div>
  components
</div>

<div>
  UNIT IV
</div>

<div>
  1. Explain the three dimensional display methods?
</div>

<div>
  • Parallel projection
</div>

<div>
  • The production of the 2D display of the 3D scene is
</div>

<div>
  called projection
</div>

<div>
  • Project points on the object surface along the parallel
</div>

<div>
  lines on to the display plane
</div>

<div>
  • Different 2D views of objects can be produced by
</div>

<div>
  projecting the visible points
</div>

<div>
  • Perspective projection
</div>

<div>
  • Done by the projecting points to the display plane
</div>

<div>
  along the converging points
</div>

<div>
  • Causes the objects farther from the viewing point
</div>

<div>
  should be smaller of the same sized object present here.
</div>

<div>
  • Depth CUEING
</div>

<div>
  • Basic problem for visualization techniques is called
</div>

<div>
  depth cueing
</div>

<div>
  • Some 3D objects are without depth information
</div>

<div>
  • Visible line and surface identification
</div>

<div>
  • To highlight the visible lines
</div>

<div>
  • Display visible lines as dashed lines
</div>

<div>
  26
</div>

<div>
  • Removing the invisible lines
</div>

<div>
  • Surface rendering
</div>

<div>
  • Lightening conditions in the screen
</div>

<div>
  • Assigned characteristics
</div>

<div>
  • Degree of transparency
</div>

<div>
  • How rough or smooth the surfaces are to be
</div>

<div>
  • Exploded and cutaway views
</div>

<div>
  • Three dimensional and stereoscopic views
</div>

<div>
  2. Explain spline representation
</div>

<div>
  • It is referred to a curve drawn in a different manner
</div>

<div>
  • Interpolation and approximation splines
</div>

<div>
  • Set of coordinate points called control points
</div>

<div>
  • Curve can be translated , rotated and scaled
</div>

<div>
  • Enclosing a set of points called convex hull
</div>

<div>
  • Set of connected points is often called control graph
</div>

<div>
  • Parametric continuity condition
</div>

<div>
  • Geometric continuity condition
</div>

<div>
  • Spline specification
</div>

<div>
  3. Explain Bezier curves and surfaces
</div>

<div>
  • Have number of properties
</div>

<div>
  • Can be fitted to any number of control points
</div>

<div>
  • Polynomial functions between p0 and pn
</div>

<div>
  n
</div>

<div>
  P(u) = Σ pk BEZ k,n(u)
</div>

<div>
  K = 0
</div>

<div>
  • Calculated x(u), y(u), z(u)
</div>

<div>
  • Properties of Bezier curves
</div>

<div>
  • Cubic Bezier curves
</div>

<div>
  • Design techniques in Bezier curves
</div>

<div>
  • Bezier surfaces
</div>

<div>
  27
</div>

<div>
  4. Explain general three dimensional rotations
</div>

<div>
  • Transformation sequences
</div>

<div>
  • P’ = T’.Rx (θ) .T.P
</div>

<div>
  • Rotation in five steps
</div>

<div>
  • Translate the object that rotates in parallel coordinate
</div>

<div>
  axis
</div>

<div>
  • Rotate the object with one coordinate axis
</div>

<div>
  • Apply inverse rotation to its original position
</div>

<div>
  • Apply inverse translation to its original position
</div>

<div>
  • V = p2 – p1
</div>

<div>
  • After rotation to original position
</div>

<div>
  R( θ ) = T’.M.T
</div>