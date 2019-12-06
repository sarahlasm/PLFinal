# GLSL: A Shading Language
*By: Alex Hamel, Katherine Hansen, Sarah Lasman, and Brandon Makin*

## About
  OpenGL Shading Language (GLSL) is a shading language with syntax similar to that of the C programming language. It was 
developed for use with Open Graphics Library (OpenGL), an application programming interface for GPUs with a focus on allowing 
2D and 3D graphics applications to be portable. GLSL was first introduced in 2004. It will continue to be used by OpenGL’s 
successor, the Vulkan graphics API.  GLSL also runs on WebGL, a variation of OpenGL that powers graphics in modern web browsers.

  In GLSL, programs called shaders are written.  These are used for rendering graphics in real-time. Rather than being executed
on the central processing unit, these programs are executed on a graphics processing unit (GPU). Shaders are written to be 
massively parallel, to take advantage of the highly parallel nature of GPU computing. As a result, shaders are extremely 
performant for certain tasks -- most commonly rendering computer graphics.  In fact, the term “shader” is a reference to the 
original use of shader languages, to provide light and shadow to 3D scenes. Languages such as GLSL are therefore most commonly
used in video games or other interactive applications that need to run performantly.

  There are a few different types of shaders that can be built with GLSL.  The two most common are as follows: Vertex shaders 
can modify the positions of points (vertices) on objects in 3D scenes.  Fragment shaders, on the other hand, are computer per 
pixel.  Fragment shaders are used to give color to 2D images or to the surfaces of 3D objects.  Also of note are compute 
shaders. Computer shaders are shaders that perform arbitrary tasks (that may not even have anything to do with graphics) and 
are handy for any miscellaneous problem that can be split up into tiny, parallelizable subtasks.

  The two most common shader languages are GLSL and HLSL.  Just as GLSL is built for OpenGL, HLSL is a language built for 
Microsoft’s Direct3D graphics API.  While GLSL is a cross-platform, open standard, HLSL and Direct3D are proprietary and 
exclusive to Microsoft’s Windows and Xbox platforms.  While similar programs can be made in each language, we ultimately chose 
GLSL for its compatibility with web browsers.

  We wanted to learn about GLSL because of its use in video games.  All shading in 3D games (and in some 2D games) is done with
shader languages.  Additionally, compute shaders are useful for “particle systems”: systems of hundreds or thousands of objects
in the world of a game or simulation that behave according to some basic physics. Particle systems may be used, for instance, 
to efficiently simulate water, fire, firework shows, or swarms of bugs.

  The language does not have all the functionality of more general languages, due to its domain-specific applications. While it
does contain integers, floats, booleans, and doubles, there are no characters or strings, since there would be no use for them 
visually. GLSL makes heavy use of vectors and matrices.

  Besides games, many visualization programs use OpenGL, including Google Earth, which visualizes the earth’s surface; PyMol, a
molecular visualization system; and Stellarium, a simulator of the night sky.

## Getting Started

Here are the specs! They're a bit too long to read in one go, but useful information if you want to look up something specific.
https://www.khronos.org/registry/OpenGL/specs/gl/GLSLangSpec.4.50.pdf

Some basic tutorials on GLSL:
https://learnopengl.com/Getting-started/Shaders

A site to let you play around:
http://shdr.bkcore.com/

## Fun Images

## References
1. https://www.khronos.org/opengl/wiki/History_of_OpenGL
2. https://www.khronos.org/registry/OpenGL/specs/gl/GLSLangSpec.1.20.pdf 
3. https://en.wikipedia.org/wiki/OpenGL_Shading_Language 
4. https://learnopengl.com/Getting-started/Shaders
5. https://en.wikibooks.org/wiki/GLSL_Programming/Introduction
6. http://nehe.gamedev.net/article/glsl_an_introduction/25007/
