## Intro to WebGL & Three.js


### WebGL
* JavaScript API for rendering interactive 2D and 3D graphics
inside an HTML `<canvas>` element.
* WebGL programs consist of control code written in mostly JS that is executed on a computer's Graphics Processing Unit (GPU)
* Best browser for WebGL : Chrome!   *(Firefox, Safari work too)*

### Examples
* [Jellyfish](https://jayweeks.com/medusae/)
* [Flamingo](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwi29_jM7-fLAhVP6WMKHcWqAT4QFggdMAA&url=http%3A%2F%2Fpablotheflamingo.com%2F&usg=AFQjCNF2Ij3h_HjVNtd0rtV4cVwonIyK_Q&sig2=9QUXGYO5OAWD1BzMMqIbfg)
* [PlayMapsCube](http://www.playmapscube.com/)

### Basics of digital 3D space
* Mesh : refers to the object's outer shape (i.e. Cube or Sphere)
* Material : type of covering on a mesh (i.e. Lambert or Phong)
* Texture : an overlay on the material (i.e. an image of rock texture can overlay a sphere to make it look like a rock)
* Camera
* Light
* Scene : everything in the browser that could be rendered
* Renderer : the main processor that allows you to see your scene

### Three.js
* A library *for* the web graphics library (webGL)
* Important because it lowers the barrier of entry for WebGL
* Provides APIs for renderers, cameras, shaders, lighting, scenes, etc.
* Very new and doesn't have much documentation, but the actual API does abstract away the difficulty of WebGL itself



##### Other Resources
* [Chrome Experiments](https://www.chromeexperiments.com/webgl)
* [Basic tutorial](http://www.html5rocks.com/en/tutorials/three/intro/)
* [Awesome interactive slideshow on Three.js](http://davidscottlyons.com/threejs/presentations/frontporch14/#slide-0)
* [Three.js documentation](http://threejs.org/)
