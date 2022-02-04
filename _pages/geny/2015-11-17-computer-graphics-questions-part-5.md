---
id: 62
title: Computer Graphics Questions Part 5
date: 2015-11-17T21:52:00+00:00
author: chito
layout: post
guid: http://www.afriqueunique.org/2015/11/17/12097749/
permalink: /2015/11/17/computer-graphics-questions-part-5/
swp_pinterest_image_url:
  - ""
swp_cache_timestamp:
  - "419230"
post_views_count:
  - "156"
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
  - "1570415414"
categories:
  - LEARNING
---
<div>
  17. What is a bitmapped font?
</div>

<div>
  A simple method for representing the character shapes in a particular typeface is
</div>

<div>
  to use rectangular grid patterns. The set of characters are then referred to as a bitmap font.
</div>

<div>
  18. What is an outline font?
</div>

<div>
  A flexible scheme is to describe character shapes using straight-line and curve
</div>

<div>
  sections. In this case, the set of character is called an out line font.
</div>

<div>
  19. What is an attribute parameter?
</div>

<div>
  Any parameter that affects the way a primitive is to be displayed is referred to as
</div>

<div>
  an attribute parameter.
</div>

<div>
  20. What are the various attributes of a line?
</div>

<div>
  The line type, width and color are the attributes of the line. The line type include
</div>

<div>
  solid line, dashed lines, and dotted lines.
</div>

<div>
  21. What is pixel mask?
</div>

<div>
  Pixel mask is a string containing the digits 1 and 0 to indicate which positions to
</div>

<div>
  plot along the line path. The mask 1111000, could be used to display a dashed line with a
</div>

<div>
  dash length of 4 and inter dot spacing of three.
</div>

<div>
  22. What is a Line cap?
</div>

<div>
  Line caps can be used to adjust the shape of the line ends to give a better
</div>

<div>
  appearance. There are three types of line caps. Butt cap which has a square end, round
</div>

<div>
  cap which has a semi circle end, projecting square cap which has one half of the line
</div>

<div>
  width beyond the specified end points.
</div>

<div>
  23. List out the methods used for smoothly joining two line segments?
</div>

<div>
  Mitter join- by extending the outer boundaries of each of the two lines
</div>

<div>
  until they meet.
</div>

<div>
  Round join – by capping the connection between the two segments with a
</div>

<div>
  circular boundary whose diameter is equal to the line width.
</div>

<div>
  Bevel join – by displaying the line segments with butt caps and filling in
</div>

<div>
  the triangular gap where the segment meet.
</div>

<div>
  24. What is Color Look up table?
</div>

<div>
  In color displays, 24 bits per pixel are commonly used, where 8 bits represent 256
</div>

<div>
  level for each color. It is necessary to read 24- bit for each pixel from frame buffer. This
</div>

<div>
  is very time consuming. To avoid this video controller uses look up table to store many
</div>

<div>
  entries to pixel values in RGB format. This look up table is commonly known as colour
</div>

<div>
  table.
</div>

<div>
  25. What is tiling patterns?
</div>

<div>
  The process of filling an area with rectangular pattern is called tiling and
</div>

<div>
  rectangular fill patterns are sometimes referred to as tiling patterns.
</div>

<div>
  26. What is soft fill?
</div>

<div>
  Soft fill is a filling method in which fill color is combined with the background
</div>

<div>
  colors.
</div>

<div>
  7
</div>

<div>
  27. What is kerned character?
</div>

<div>
  The characters which extend beyond the character body limits is known as kerned
</div>

<div>
  character. Example f and j.
</div>

<div>
  28. What is character up vector?
</div>

<div>
  The orientation for a displayed character string is set according to the direction of
</div>

<div>
  the character up vector.
</div>

<div>
  29. Define bundled attributes?
</div>

<div>
  Individual attribute commands provide a simple and direct method for specifying
</div>

<div>
  attributes when a single output device is used. When several kinds of output device are
</div>

<div>
  available at a graphics installation, it is convenient to set up a table for each output device
</div>

<div>
  that lists set of attribute values that are to be used on that device to display each primitive
</div>

<div>
  type. Attribute specified in this manner is known as bundled attribute.
</div>

<div>
  30. What is aliasing?
</div>

<div>
  In the line drawing algorithms, all rasterzed locations do not match with the true
</div>

<div>
  line and have to represent a straight line. This problem is severe in low resolution
</div>

<div>
  screens. In such screens line appears like a stair-step. This effect is known as aliasing.
</div>

<div>
  31. What is antialiasing?
</div>

<div>
  The process of adjusting intensities of the pixels along the line to minimize the
</div>

<div>
  effect of aliasing is called antialiasing.
</div>

<div>
  32. What is pixel phasing?
</div>

<div>
  Pixel phasing is an antialiasing technique, stair steps are smoothed out by moving
</div>

<div>
  the electron beam to more nearly approximate positions specified by the object geometry.
</div>

<div>
  UNIT – III
</div>

<div>
  1. What is Transformation?
</div>

<div>
  Transformation is the process of introducing changes in the shape size and
</div>

<div>
  orientation of the object using scaling rotation reflection shearing & translation etc.
</div>

<div>
  2. Write short notes on active and passive transformations?
</div>

<div>
  In the active transformation the points x and x| represent different coordinates of
</div>

<div>
  the same coordinate system. Here all the points are acted upon by the same
</div>

<div>
  transformation and hence the shape of the object is not distorted. In a passive
</div>

<div>
  transformation the points x and x| represent same points in the space but in a different
</div>

<div>
  coordinate system. Here the change in the coordinates is merely due to the change in
</div>

<div>
  the type of the user coordinate system.
</div>

<div>
  3. What is translation?
</div>

<div>
  Translation is the process of changing the position of an object in a straight-line
</div>

<div>
  path from one coordinate location to another. Every point (x , y) in the object must
</div>

<div>
  under go a displacement to (x|,y|). the transformation is:
</div>

<div>
  x
</div>

<div>
  |
</div>

<div>
  = x + tx ; y| = y+ty
</div>

<div>
  8
</div>

<div>
  4. What is rotation?
</div>

<div>
  A 2-D rotation is done by repositioning the coordinates along a circular path, in
</div>

<div>
  the x-y plane by making an angle with the axes. The transformation is given by: X| = r
</div>

<div>
  cos (θ + φ) and Y| = r sin (θ + φ).
</div>

<div>
  5. What is scaling?
</div>

<div>
  The scaling transformations changes the shape of an object and can be carried out
</div>

<div>
  by multiplying each vertex (x,y) by scaling factor Sx,Sy where Sx is the scaling factor
</div>

<div>
  of x and Sy is the scaling factor of y.
</div>

<div>
  6. What is shearing?
</div>

<div>
  The shearing transformation actually slants the object along the X direction or the
</div>

<div>
  Y direction as required.ie; this transformation slants the shape of an object along a
</div>

<div>
  required plane.
</div>

<div>
  7. What is reflection?
</div>

<div>
  The reflection is actually the transformation that produces a mirror image of an
</div>

<div>
  object. For this use some angles and lines of reflection.
</div>

<div>
  8. Distinguish between window port & view port?
</div>

<div>
  A portion of a picture that is to be displayed by a window is known as window
</div>

<div>
  port. The display area of the part selected or the form in which the selected part is
</div>

<div>
  viewed is known as view port.
</div>

<div>
  9. Define clipping?
</div>

<div>
  Clipping is the method of cutting a graphics display to neatly fit a predefined
</div>

<div>
  graphics region or the view port.
</div>

<div>
  10. What is covering (exterior clipping)?
</div>

<div>
  This is just opposite to clipping. This removes the lines coming inside the
</div>

<div>
  windows and displays the remaining. Covering is mainly used to make labels on the
</div>

<div>
  complex pictures.
</div>

<div>
  11. What is the need of homogeneous coordinates?
</div>

<div>
  To perform more than one transformation at a time, use homogeneous coordinates
</div>

<div>
  or matrixes. They reduce unwanted calculations intermediate steps saves time and
</div>

<div>
  memory and produce a sequence of transformations.
</div>

<div>
  12. Distinguish between uniform scaling and differential scaling?
</div>

<div>
  When the scaling factors sx and sy are assigned to the same value, a uniform
</div>

<div>
  scaling is produced that maintains relative object proportions. Unequal values for sx and
</div>

<div>
  sy result in a differential scaling that is often used in design application.
</div>

<div>
  13. What is fixed point scaling?
</div>

<div>
  The location of a scaled object can be controlled by a position called the fixed
</div>

<div>
  point that is to remain unchanged after the scaling transformation.
</div>