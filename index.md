---
layout: default
title: Quick Start
nav_order: 1
---

## Quick Start

First of all, you need to unpack the right packages for your specific setup of Unity. This Asset contains three packages, for **Standard**, **HDRP**, and **URP** pipelines. Start with **Step_1_CoreResources** package, it will add all core resources (textures, scripts, and meshes) needed for this Asset. After that, pick the right SRP package and unpack it too. It will add all other components like prefabs of complete effects, scenes, materials, and shaders. If you using Standard pipeline and already have PostProcessing Stack V2 in your project, you can uncheck it when unpacking the **Standard** package. WWWw

### Important Notes

* **(URP)** Make sure, you enable HDR in URP Asset settings.

![s35](/assets/images/Screenshot_35.png)

* **(Standard)** Turn on "HDR" on your Camera, Shaders requires it.

![s18](/assets/images/Screenshot_18.png)

* **(All)** This VFX Asset looks much better in "Linear" Color Space, but if you using "Gamma" Color Space, you need to slightly decrease the Final Power (Emission Power) material parameter of each effect. You can check it in the "Edit > Project Settings > Player" TAB.
* **(All)** Image Effects are necessary in order to make a great-looking game, as well as our asset. Be sure to use "ACES Tone Mapping" and "Bloom".



### How To Use

* First of all, check the "DemoScene", it contains all the materials and nice way to quickly preview them on various meshes.
* You can just apply any material from the "Resources/Materials" folder to any mesh. But it is recommended to use meshes with smooth normals.
* It is also possible to plug the corresponding normal map of the mesh to "Normal" texture slot, it will lead to a slightly different rim effect. But it is not necessary at all, some meshes will look better without using their baked normal textures with these materials.



### Support email: sinevfx@gmail.com
