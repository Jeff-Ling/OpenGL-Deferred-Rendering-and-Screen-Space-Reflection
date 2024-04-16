# OpenGL-Deferred-Rendering-and-Screen-Space-Reflection
CIS 561 Project - Deferred Rendering and SSR

 - Programmed `g-buffer.frag.glsl` shader to store data in multiple output channels, facilitating the rendering of accurate reflections of objects on other objects within a scene.
 - Computed screen-space reflections by determining intersection points within the G-buffer, enhancing the realism of reflections in 3D environments.
 - Created and integrated a Gaussian kernel for blurred reflections to simulate glossy reflections of rough surfaces, utilizing `blur.frag.glsl` for applying Gaussian blur to specular reflections.
 - Combined rendered elements using `combine.frag.glsl`, integrating reflection colors with the PBR for final image synthesis, achieving visually coherent and dynamic scenes.

![Render1](https://github.com/Jeff-Ling/OpenGL-Deferred-Rendering-and-Screen-Space-Reflection/assets/74678923/a75e3a2a-e4ae-4783-9326-201b87aeedbe)
