# Fast-Quadric-Mesh-Simplification
Mesh triangle reduction using quadrics - for Windows, OSX and Linux (thx Chris Rorden)

![img](https://github.com/sp4cerat/Fast-Quadric-Mesh-Simplification/blob/master/screenshot.png?raw=true)

**Summary** This is my own version of the Fast-Quadric-Mesh-Simplification code written by [sp4cerat](https://github.com/sp4cerat) and [Chris Rorden](https://github.com/neurolabusc), to which I only have added small optimizations and code clean-up. All credit  goes to the original authors.

**Usage** The functionality is contained in Simplify.h. The function to call is *simplify_mesh(target_count)*. The code is kept pretty slim, so the main method has just around 400 lines of code. 

**Obj File Limitations** The Obj file may only have one group or object. Its a very simple reader/writer, so dont try to use multiple objects in one file

License : MIT

Please dont forget to cite [this page](https://github.com/sp4cerat/Fast-Quadric-Mesh-Simplification) if you use the code!
