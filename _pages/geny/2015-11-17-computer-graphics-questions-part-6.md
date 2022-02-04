---
id: 5781
title: Computer Graphics Questions Part 6
date: 2015-11-17T21:54:00+00:00
author: chito
layout: post
guid: http://www.afriqueunique.org/2015/11/17/12097761/
permalink: /2015/11/17/computer-graphics-questions-part-6/
swp_pinterest_image_url:
  - ""
swp_cache_timestamp:
  - "421692"
post_views_count:
  - "83"
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
  - "1568087899"
categories:
  - LEARNING
---
<div>
  14. Define Affine transformation?
</div>

<div>
  A coordinate transformation of the form
</div>

<div>
  X= a
</div>

<div>
  xxx + axyy + bx , y ’ ayxx + ayy y +by
</div>

<div>
  is called a two-dimensional affine transformation. Each of the transformed
</div>

<div>
  coordinates x ‘ and y ‘ is a linear function of the original coordinates x and y , and
</div>

<div>
  parameters aij and bk are constants determined by the transformation type.
</div>

<div>
  15. Distinguish between bitBlt and pixBlt?
</div>

<div>
  Raster functions that manipulate rectangular pixel arrays are generally referred to
</div>

<div>
  as raster ops. Moving a block of pixels from one location to another is also called a block
</div>

<div>
  transfer of pixel values. On a bilevel system, this operation is called a bitBlt (bit-block
</div>

<div>
  transfer), on multilevel system t is called pixBlt.
</div>

<div>
  16. List out the various Text clipping?
</div>

<div>
  All-or-none string clipping &#8211; if all of the string is inside a clip window, keep it
</div>

<div>
  otherwise discards.
</div>

<div>
  All-or-none character clipping – discard only those characters that are not
</div>

<div>
  completely inside the window. Any character that either overlaps or is outside a
</div>

<div>
  window boundary is clipped.
</div>

<div>
  Individual characters – if an individual character overlaps a clip window
</div>

<div>
  boundary, clip off the parts of the character that are outside the window.
</div>

<div>
  UNIT – IV
</div>

<div>
  1. What are the various representation schemes used in three dimensional objects?
</div>

<div>
  Boundary representation (B-res) – describe the 3 dimensional object as a set of
</div>

<div>
  surfaces that separate the object interior from the environment.
</div>

<div>
  Space- portioning representation – describe interior properties, by partitioning the
</div>

<div>
  spatial region containing an object into a set of small, no overlapping, contiguous
</div>

<div>
  solids.
</div>

<div>
  2. What is Polygon mesh?
</div>

<div>
  Polygon mesh is a method to represent the polygon, when the object surfaces are
</div>

<div>
  tiled, it is more convenient to specify the surface facets with a mesh function. The various
</div>

<div>
  meshes are
</div>

<div>
  Triangle strip – (n-2) connected triangles
</div>

<div>
  Quadrilateral mesh – generates (n-1)(m-1) Quadrilateral
</div>

<div>
  3. What is Bezier Basis Function?
</div>

<div>
  Bezier Basis functions are a set of polynomials, which can be used instead of the
</div>

<div>
  primitive polynomial basis, and have some useful properties for interactive curve design.
</div>

<div>
  4. What is surface patch?
</div>

<div>
  A single surface element can be defined as the surface traced out as two
</div>

<div>
  parameters (u, v) take all possible values between 0 and 1 in a two-parameter
</div>

<div>
  representation. Such a single surface element is known as a surface patch.
</div>

<div>
  10
</div>

<div>
  5. Write short notes on rendering bi-cubic surface patches of constant u and v method?
</div>

<div>
  The simple way is to draw the iso-parmetric lines of the surface. Discrete
</div>

<div>
  approximations to curves on the surface are produced by holding one parameter constant
</div>

<div>
  and allowing the other to vary at discrete intervals over its whole range. This produce
</div>

<div>
  curves of constant u and constant v.
</div>

<div>
  6. What are the advantages of rendering polygons by scan line method?
</div>

<div>
  i. The max and min values of the scan were easily found.
</div>

<div>
  ii. The intersection of scan lines with edges is easily calculated by a simple
</div>

<div>
  incremental method.
</div>

<div>
  iii. The depth of the polygon at each pixel is easily calculated by an
</div>

<div>
  incremental method.
</div>

<div>
  7. What are the advantages of rendering by patch splitting?
</div>

<div>
  i. It is fast- especially on workstations with a hardware polygon-rendering
</div>

<div>
  pipeline.
</div>

<div>
  ii. It’s speed can be varied by altering the depth of sub-division.
</div>

<div>
  8. Define B-Spline curve?
</div>

<div>
  A B-Spline curve is a set of piecewise(usually cubic) polynomial segments that
</div>

<div>
  pass close to a set of control points. However the curve does not pass through these
</div>

<div>
  control points, it only passes close to them.
</div>

<div>
  9. What is a spline?
</div>

<div>
  To produce a smooth curve through a designed set of points, a flexible strip called
</div>

<div>
  spline is used. Such a spline curve can be mathematically described with a piecewise
</div>

<div>
  cubic polynomial function whose first and second derivatives are continuous across
</div>

<div>
  various curve section.
</div>

<div>
  10. What is the use of control points?
</div>

<div>
  Spline curve can be specified by giving a set of coordinate positions called control
</div>

<div>
  points, which indicates the general shape of the curve, can specify spline curve.
</div>

<div>
  11. What are the different ways of specifying spline curve?
</div>

<div>
  • Using a set of boundary conditions that are imposed on the spline.
</div>

<div>
  • Using the state matrix that characteristics the spline
</div>

<div>
  • Using a set of blending functions that calculate the positions along the
</div>

<div>
  curve path by specifying combination of geometric constraints on the
</div>

<div>
  curve
</div>

<div>
  12. What are the important properties of Bezier Curve?
</div>

<div>
  • It needs only four control points
</div>

<div>
  • It always passes through the first and last control points
</div>

<div>
  • The curve lies entirely within the convex half formed by four control
</div>

<div>
  points.
</div>

<div>
  11
</div>

<div>
  13. Differentiate between interpolation spline and approximation spline?
</div>

<div>
  When the spline curve passes through all the control points then it is called
</div>

<div>
  interpolate. When the curve is not passing through all the control points then that curve is
</div>

<div>
  called approximation spline.
</div>

<div>
  14. What do you mean by parabolic splines?
</div>

<div>
  For parabolic splines a parabola is fitted through the first three points p1,p2,p3 of
</div>

<div>
  the data array of kot points. Then a second parabolic arc is found to fit the sequence of
</div>

<div>
  points p2, p3, p4. This continues in this way until a parabolic arc is found to fit through
</div>

<div>
  points pn-2, pn-1 and pn. The final plotted curve is a meshing together of all these
</div>

<div>
  parabolic arcs.
</div>

<div>
  15. What is cubic spline?
</div>

<div>
  Cubic splines are a straight forward extension of the concepts underlying
</div>

<div>
  parabolic spline. The total curve in this case is a sequence of arcs of cubic rather than
</div>

<div>
  parabolic curves
</div>

<div>
  Each cubic satisfies :ax3 + bx 2+ cx + d
</div>

<div>
  16. What is a Blobby object?
</div>

<div>
  Some objects do not maintain a fixed shape, but change their surface
</div>

<div>
  characteristics in certain motions or when in proximity to other objects. That is known as
</div>

<div>
  blobby objects. Example – molecular structures, water droplets.
</div>

<div>
  17. Define Octrees?
</div>

<div>
  Hierarchical tree structures called octrees, are used to represent solid objects in
</div>

<div>
  some graphics systems. Medical imaging and other applications that require displays of
</div>

<div>
  object cross sections commonly use octree representation.
</div>

<div>
  18. Define Projection?
</div>

<div>
  The process of displaying 3D into a 2D display unit is known as
</div>

<div>
  projection. The projection transforms 3D objects into a 2D projection plane.
</div>

<div>
  19. What are the steps involved in 3D transformation?
</div>

<div>
  • Modeling Transformation
</div>

<div>
  • Viewing Transformation
</div>

<div>
  • Projection Transformation
</div>

<div>
  • Workstation Transformation
</div>

<div>
  20. What do you mean by view plane?
</div>

<div>
  A view plane is nothing but the film plane in camera which is positioned
</div>

<div>
  and oriented for a particular shot of the scene.
</div>

<div>
  21. What is view-plane normal vector?
</div>

<div>
  This normal vector is the direction perpendicular to the view plane and it
</div>

<div>
  is called as [DXN DYN DZN]
</div>

<div>
  12
</div>

<div>
  22. What is view distance?
</div>

<div>
  The view plane normal vector is a directed line segment from the view
</div>

<div>
  plane to the view reference point. The length of this directed line segment is referred
</div>

<div>
  to as view distance
</div>

<div>
  23. Define projection?
</div>

<div>
  The process of converting the description of objects from world
</div>

<div>
  coordinates to viewing coordinates is known as projection
</div>

<div>
  24. What you mean by parallel projection?
</div>

<div>
  Parallel projection is one in which z coordinates is discarded and parallel
</div>

<div>
  lines from each vertex on the object are extended until they intersect the view plane.
</div>

<div>
  25. What do you mean by Perspective projection?
</div>

<div>
  Perspective projection is one in which the lines of projection are not
</div>

<div>
  parallel. Instead, they all converge at a single point called the center of projection.
</div>

<div>
  26. What is Projection reference point?
</div>

<div>
  In Perspective projection, the lines of projection are not parallel. Instead,
</div>

<div>
  they all converge at a single point called Projection reference point.
</div>

<div>
  27. What is the use of Projection reference point?
</div>

<div>
  In Perspective projection, the object positions are transformed to the view
</div>

<div>
  plane along these converged projection line and the projected view of an object is
</div>

<div>
  determined by calculating the intersection of the converged projection lines with the
</div>

<div>
  view plane.
</div>

<div>
  28. What are the different types of parallel projections?
</div>

<div>
  The parallel projections are basically categorized into two types,
</div>

<div>
  depending on the relation between the direction of projection and the normal to the
</div>

<div>
  view plane. They are orthographic parallel projection and oblique projection.
</div>

<div>
  29. What is orthographic parallel projection?
</div>

<div>
  When the direction of the projection is normal (perpendicular) to the view
</div>

<div>
  plane then the projection is known as orthographic parallel projection
</div>

<div>
  30. What is orthographic oblique projection?
</div>

<div>
  When the direction of the projection is not normal (not perpendicular) to
</div>

<div>
  the view plane then the projection is known as oblique projection.
</div>

<div>
  31. What is an axonometric orthographic projection?
</div>

<div>
  The orthographic projection can display more than one face of an object.
</div>

<div>
  Such an orthographic projection is called axonometric orthographic projection.
</div>

<div>
  32. What is cavalier projection?
</div>

<div>
  The cavalier projection is one type of oblique projection, in which the
</div>

<div>
  direction of projection makes a 45-degree angle with the view plane.
</div>

<div>
  13
</div>

<div>
  33. What is cabinet projection?
</div>

<div>
  The cabinet projection is one type of oblique projection, in which the
</div>

<div>
  direction of projection makes a n angle of arctan (2)=63.4- with the view plane.
</div>

<div>
  34. What is vanishing point?
</div>

<div>
  The perspective projections of any set of parallel lines that are not parallel
</div>

<div>
  to the projection plane converge to appoint known as vanishing point.
</div>

<div>
  35. What do you mean by principle vanishing point.
</div>

<div>
  The vanishing point of any set of lines that are parallel to one of the three
</div>

<div>
  principle axes of an object is referred to as a principle vanishing point or axis
</div>

<div>
  vanishing point.
</div>

<div>
  36. What is view reference point?
</div>

<div>
  The view reference point is the center of the viewing coordinate system. It
</div>

<div>
  is often chosen to be close to or on the surface of the some object in the scene.
</div>

<div>
  UNIT – V
</div>

<div>
  1. Define computer graphics animation?
</div>

<div>
  Computer graphics animation is the use of computer graphics equipment
</div>

<div>
  where the graphics output presentation dynamically changes in real time. This is often
</div>

<div>
  also called real time animation.
</div>

<div>
  2. What is tweening?
</div>

<div>
  It is the process, which is applicable to animation objects defined by a
</div>

<div>
  sequence of points, and that change shape from frame to frame.
</div>

<div>
  3. Define frame?
</div>

<div>
  One of the shape photographs that a film or video is made of is known as
</div>

<div>
  frame.
</div>

<div>
  4. What is key frame?
</div>

<div>
  One of the shape photographs that a film or video is made of the shape of
</div>

<div>
  an object is known initially and for a small no of other frames called keyframe
</div>

<div>
  5. What is pseudo animation?
</div>

<div>
  Pseudo animation is creating a sequence of stills, photographing or video
</div>

<div>
  graphing each still as one frame, and then later playing back the frames at a faster
</div>

<div>
  speed.
</div>

<div>
  6. What is the normal speed of a visual animation?
</div>

<div>
  Visual animation requires a playback of at least 25 frames per second.
</div>

<div>
  14
</div>

<div>
  7. What are the different tricks used in computer graphics animation?
</div>

<div>
  a. Color look Up Table manipulation
</div>

<div>
  b. Bit plane manipulation
</div>

<div>
  c. Use of UDCS
</div>

<div>
  d. Special drawing modes
</div>

<div>
  e. Sprites
</div>

<div>
  f. Bit blitting
</div>

<div>
  8. What is color look up table?
</div>

<div>
  In color display unit it is necessary to read 44-bit for each pixel from
</div>

<div>
  buffer. This very time consuming process. To avoid this video controller uses look up
</div>

<div>
  table to store many entries of pixel vales in RGB format. This look up table is
</div>

<div>
  commonly known as color look up table.
</div>

<div>
  9. What is solid modeling?
</div>

<div>
  The construction of 3 dimensional objects for graphics display is often
</div>

<div>
  referred to as solid modeling.
</div>

<div>
  10. What is an intuitive interface?
</div>

<div>
  The intuitive interface is one, which simulates the way a person would
</div>

<div>
  perform a corresponding operation on real object rather than have menu command.
</div>

<div>
  11. What is Sprite?
</div>

<div>
  A Sprite is graphics shape in animation and games programs. Each sprite
</div>

<div>
  provided in the system has its own memory area similar to but smaller than pixel
</div>

<div>
  RAM.
</div>

<div>
  12. What is the UDC technique?
</div>

<div>
  UDC stands for User Defined Character set. It is graphics animation trick,
</div>

<div>
  which is used in early microcomputer system.
</div>

<div>
  13. What is the use of hidden line removing algorithm?
</div>

<div>
  The hidden line removal algorithm determines the lines, edges, surfaces or
</div>

<div>
  volumes that are visible or invisible to an observer located at a specific point in space.
</div>

<div>
  14. What is computer graphics realism?
</div>

<div>
  The creation of realistic picture in computer graphics is known as realism.
</div>

<div>
  It is important in fields such as simulation, design, entertainments, advertising,
</div>

<div>
  research, education, command, and control.
</div>

<div>
  15. How realistic pictures are created in computer graphics?
</div>

<div>
  To create a realistic picture, it must be process the scene or picture through
</div>

<div>
  viewing-coordinate transformations and projection that transform three-dimensional
</div>

<div>
  viewing coordinates onto two-dimensional device coordinates.
</div>

<div>
  16. What is Fractals?
</div>

<div>
  A Fractal is an object whose shape is irregular at all scales.
</div>

<div>
  15
</div>

<div>
  17. What is a Fractal Dimension?
</div>

<div>
  Fractal has infinite detail and fractal dimension. A fractal imbedded in ndimensional space could have any fractional dimension between 0 and n. The Fractal
</div>

<div>
  Dimension D= LogN / Log S
</div>

<div>
  Where N is the No of Pieces and S is the Scaling Factor.
</div>

<div>
  18. What is random fractal?
</div>

<div>
  The patterns in the random fractals are no longer perfect and the random
</div>

<div>
  defects at all scale.
</div>

<div>
  19. What is geometric fractal?
</div>

<div>
  A geometric fractal is a fractal that repeats self-similar patterns over all
</div>

<div>
  scales.
</div>

<div>
  20. What is Koch curve?
</div>

<div>
  The Koch curve can be drawn by dividing line into 4 equal segments with
</div>

<div>
  scaling factor 1/3. and middle 2 segments are so adjusted that they form adjustment
</div>

<div>
  sides of an equilateral triangle.
</div>

<div>
  21. What is turtle graphics program?
</div>

<div>
  The turtle program is a Robert that can move in 2 dimensions and it has a
</div>

<div>
  pencil for drawing. The turtle is defined by the following parameters.
</div>

<div>
  g. Position of the turtle (x, y)
</div>

<div>
  h. Heading of the turtle 0 the angle from the x axis.
</div>

<div>
  22. What is graftals?
</div>

<div>
  Graftals are applicable to represent realistic rendering plants and trees. A
</div>

<div>
  tree is represented by a String of symbols 0, 1, [, ]
</div>

<div>
  23. What is a Particle system?
</div>

<div>
  A particle system is a method for modeling natural objects, or other
</div>

<div>
  irregularly shaped objects, that exhibit “fluid-like” properties. Particle systems are
</div>

<div>
  suitable for realistic rendering of fuzzy objects, smoke, sea and grass.
</div>

<div>
  24. Give some examples for computer graphics standards?
</div>

<div>
  i. CORE – The Core graphics standard
</div>

<div>
  j. GKS &#8212; The Graphics Kernel system
</div>

<div>
  k. PHIGS – The Programmers Hierarchical Interactive Graphics System.
</div>

<div>
  l. GSX – The Graphics system extension
</div>

<div>
  m. NAPLPS – The North American presentation level protocol syntax.
</div>