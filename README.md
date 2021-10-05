## Simple GLTF example

avatar.glb is an avatar created by [readyplayer.me](https://readyplayer.me).

We extracted the gltf and texture with [github.com/najadojo/gltf-import-export](https://github.com/najadojo/gltf-import-export).

You can see that there is a hair bump map, and separate textures for the skin, hair, clothing, eyes, and makeup, corresponding to each of the things you can choose between in the avatar creator.  The meshes are designed with u/v coordinates to index into the texture, assuming the correct textures are assigned to the correct meshes.

You can view the avatar using [Don McCurdy's GLTF viewer](https://gltf-viewer.donmccurdy.com/) (just drop the glb on it)