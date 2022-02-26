# stackexchangeresources

**resources in this repo**
- an example of my model scan
- an image showing the goal

## Original Question

**title**
- programmatically turning a 3d scan model into a 2d outline

**intended use**
- turn a 3d model created by lidar scan into a 2d floorplan

**starting point**
- scan captured using ARkit’s Scene Reconstruction API
- saved as .obj file

**acceptable outputs**
I’m not super well versed in graphics file formats, but I’d like to be able to access coordinate/line data, if possible
- vector image format like svg (this type preferred)
- png, jpeg

**desired features**
- can exclude portions of scan captured by looking out of open windows
- can “chop off” partial scans where the walls in that part of that scan don’t form an enclosed structure (as created by looking down a hallway but not going into it)

**acceptable compromises**

 - blinds must be closed 
 - capture must form a continuous and enclosed layout (not ideal though)

**implementation priorities**
- implementation must be code I can call
- if a straightforward algorithm is a possible solution, I would like to implement inside of an ios app
- otherwise I can work with libraries in any language (python would be nice though)


----------

Any answers/ideas/research suggestions are appreciated! I posted in game dev because it seemed like the place with the most experience working with 3d models
