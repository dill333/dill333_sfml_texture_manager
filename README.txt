This is a texture loader for SFML created by me.

It's a static class in C++ that loads a texture once and then will store it.
When it is requested again, it will use the texture loaded earlier instead of reloading it.

To load a texture:
TextureManager::getTexture(<filename>);