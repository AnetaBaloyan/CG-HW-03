### CG-HW-03
# Computer Graphics Homework 03
***
**Author:** Aneta Baloyan

**Email:** _aneta_baloyan@edu.aua.am_

**University:** _American University of Armenia_
***
In this project I am drawing a cylinder object, using **OpenGL** and **C++**. The cylinder is illuminated by the **Phong illumination model**, meaning I am using an *ambient + diffuse + specular* light. 

The viewer can **rotate the object** using their mouse. There are two view options: _"game view"_ and _"rotation view"_. In the _"game view"_ one can also **move in the space** using _[W]\[A][S]\[D]_ keys. To switch to _"game view"_, just press **_[G]_**, to switch back to _"rotation view"_, press **_[R]_**. 

The program takes the following optional parameters _(must specify in the code, sorry for the bad design)_:
- **radius** of the cylinder (default: 0.5)
- **height** of the cylinder (default: 1.2)
- **bottom level** of the cylinder (default: -0.5)
- number of **vertical sectors** to approximate the cylinder (default: 500)
- number of **horizontal strips** to increaze cylinder resolution (default: 200) 
- **view type** (defaul: rotation view)
- **shininess** of the cylinder (default: 32)
- strength of the **ambient light** (default: 0.3)
- strength of the **diffuse light** (default: 1.0)
- strength of the **specular light** (default: 0.5)
- **light color** (default: pale white)
- **object color** (default: very beautiful color, just take a look)

