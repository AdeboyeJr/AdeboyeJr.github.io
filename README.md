# A-Frame Animated Scene

## Author: Adeboye Adegbenro Jr.


#### Description

Created an Animated AR/VR session using the A-Frame framework. Imported assets for the scene as GLTF files. These files make up the models, materials, textures, and animations of the objects. Website is hosted on my personal Github Pages webpage.

#### Implementation

Imported the A-Frame library and A-Frame extras modules into the HTML file. The body element contains the A-Frame scene for rendering the objects. An asset management system loads the gltf files from the assets folder to be stored in the page's memory.

```html
 <!--Asset Management System-->
<a-assets>
    <a-asset-item id="dragon" src="./assets/dragon/scene.gltf"></a-asset-item>
    <a-asset-item id="city" src="./assets/city/scene.gltf"></a-asset-item>
</a-assets>

```

Two generic entities are created and mapped to the gltf-models from the city and dragon assets.

#### Dependencies

You will need a mobile device that supports AR/VR. Web page is hosted on `![https://AdeboyeJr.github.io](https://AdeboyeJr.github.io)`
