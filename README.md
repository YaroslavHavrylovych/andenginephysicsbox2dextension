![AndEgnine_image](https://koenig-media.raywenderlich.com/uploads/2012/05/AndEngine.png)

### AndEngine tribute

[AndEngine Box 2D](https://github.com/nicolasgramlich/AndEnginePhysicsBox2DExtension/tree/GLES2-AnchorCenter/) (anchor-center) 
extension repository fork, as the main repository is out of support.
Checkout [original readme](https://github.com/nicolasgramlich/AndEnginePhysicsBox2DExtension/blob/GLES2/README.md)
file to get more information.

The game engine fork you can find [here](https://github.com/YaroslavHavrylovych/andengine).

### PROGUARD

To pass Proguard, you have to add/cover a few basic rules. These rules must be applied to the whole app, as Gradle doesn't support Proguard in sub-projects. In details AndEngine Physics Extension
forces you to next:

```
-keep public class com.badlogic.gdx.physics.box2d.World {                                                                         
  *;                                                                                                                              
}
```

### Useful links

The official AndEngine [page](http://www.andengine.org/)

The AndEngine community [page](http://andengine-community.com/)

The official extension 
[page](https://github.com/nicolasgramlich/AndEnginePhysicsBox2DExtension/tree/GLES2-AnchorCenter/).

### Changes

* Gradle support
* 64-bit architecture support (box2d files updated)
