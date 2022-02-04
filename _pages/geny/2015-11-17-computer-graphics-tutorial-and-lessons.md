---
id: 5778
title: Computer Graphics Tutorial and Lessons
date: 2015-11-17T21:59:00+00:00
author: chito
layout: post
guid: http://www.afriqueunique.org/2015/11/17/12097786/
permalink: /2015/11/17/computer-graphics-tutorial-and-lessons/
swp_pinterest_image_url:
  - ""
swp_cache_timestamp:
  - "419229"
post_views_count:
  - "111"
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
  - "1571984616"
categories:
  - LEARNING
---
<div>
  UNIT V
</div>

<div>
  1. Explain Back face detection method and Depth buffer method
</div>

<div>
  Backface Detection method
</div>

<div>
  • Fast and simple object space method
</div>

<div>
  • For identifying the back faces of a polyhedron
</div>

<div>
  • Based ion inside outside test
</div>

<div>
  • Plane parameters A, B, C, D
</div>

<div>
  Ax +By+ Cz +D < 0
</div>

<div>
  • Inside point is along the line of sight to the surface
</div>

<div>
  V.N = Vz C
</div>

<div>
  • Polygon is back face if C < 0
</div>

<div>
  • Polygon cannot see on any face if C = 0
</div>

<div>
  • Z component value is C <= 0
</div>

<div>
  Depth Buffer Method
</div>

<div>
  • To compare the surface depths at each pixel position on the plane
</div>

<div>
  projection
</div>

<div>
  • Also referred as z- buffer method
</div>

<div>
  • Two buffer areas
</div>

<div>
  • Depth buffer to store depth values
</div>

<div>
  • Refresh buffer to store intensity values
</div>

<div>
  • Depth value for a surface position (x, y)
</div>

<div>
  Z( -Ax – By – D)/C
</div>

<div>
  • Depth z’ of next position (x + 1, y)
</div>

<div>
  Z’( -A(x + 1)-By – D)/C
</div>

<div>
  29
</div>

<div>
  2. Explain area subdivision and A- Buffer method
</div>

<div>
  A Buffer Method
</div>

<div>
  • Extension idea of the depth buffer method
</div>

<div>
  • It represents an antialiased, area averaged, accumulation-buffer
</div>

<div>
  method
</div>

<div>
  • Only one visible surface
</div>

<div>
  • Two fields
</div>

<div>
  • Depth field
</div>

<div>
  Stores a positive or negative real number
</div>

<div>
  • Intensity field
</div>

<div>
  Stores a surface intensity information or a pointer
</div>

<div>
  value
</div>

<div>
  • Data for each surface in the linked list includes
</div>

<div>
  • RGB intensity components
</div>

<div>
  • Opacity parameters
</div>

<div>
  • Depth
</div>

<div>
  • Percent of area coverage
</div>

<div>
  • Surface identifier
</div>

<div>
  • Pointer to next surface
</div>

<div>
  Area Sub Division Method
</div>

<div>
  • Image space method
</div>

<div>
  • The relative characteristic of surface are
</div>

<div>
  • Surrounding surface
</div>

<div>
  • Inside surface
</div>

<div>
  • Outside surface
</div>

<div>
  • Conditions for subdivision
</div>

<div>
  • All surfaces are outside surfaces with respect to the area
</div>

<div>
  30
</div>

<div>
  • Only one inside
</div>

<div>
  • A surrounding surface with in the area boundaries
</div>

<div>
  3. Explain Depth sorting method
</div>

<div>
  • Both image and object space operations]
</div>

<div>
  • Perform the basic function
</div>

<div>
  • Surface are sorted in order of decreasing depth
</div>

<div>
  • Surface are scan converted in order, starting with the surface of
</div>

<div>
  greatest depth
</div>

<div>
  • Often referred as painters algorithm
</div>

<div>
  • Test listed in the order of increasing difficulty
</div>

<div>
  • Surface do not overlap
</div>

<div>
  • Projections of the two surfaces on to the view plane do not overlap
</div>

<div>
  4. Explain key frame systems
</div>

<div>
  Key frame systems
</div>

<div>
  • Motion path can be given with a kinematics description
</div>

<div>
  • Physically based on force acting object
</div>

<div>
  • Frame in to individual component or object called cells
</div>

<div>
  Morphing
</div>

<div>
  • Transformation of object shapes from one form to another is called
</div>

<div>
  morphing
</div>

<div>
  • Two key frames for an object transformation
</div>

<div>
  • Preprocessing using vertex count
</div>

<div>
  Simulating accelerations
</div>

<div>
  • Time interval between keyframe is divided in to n + 1
</div>

<div>
  ∆t = (t2 – t1) / n = 1
</div>

<div>
  tBj = t1 + j∆t, j = 1,2,3 ,……
</div>

<div>
  • Time for jth in- between is
</div>

<div>
  tBj = t1 + ∆t[ ( 1-cos[jπ / (n + 1)] ) / 2], j= 1, 2, 3, ….
</div>

<div>
</div>