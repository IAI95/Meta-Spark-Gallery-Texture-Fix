# Meta-Spark-Gallery-Texture-Fix

When you open a picture in your phone or computer, there are 3 types of behaviour between that picture and your screen

1. Fill // in this type of behaviour, the picture is being filled all over the screen space without caring that it's being streched or deformed (which unfortunatly Meta Spark is using this type by default)

2. Aspect Fit // in this type of behaviour, all of the picture is being shown on scren space without any deformation

3. Aspect Fill // in this type of behaviour, the picture is being zoomed in (without any deformation) untill top and bottem edges of the picture hits the boundries of the device's screen.

![Guide](https://user-images.githubusercontent.com/80382116/216987389-0ca8cdb6-d5fc-4813-969a-3e3a66a1de79.jpeg)

This simple shader fixes the Meta Spark's "Fill Texture" problem, no matter your picture is vertical, horizontal or square. there are no java script code or patches required. Just drag it in your projects and connect it to your gallery texture.

![Screenshot_1](https://user-images.githubusercontent.com/80382116/216993547-97b27fa5-2959-457d-8bec-cc40a3bc7343.png)

it has three outputs so you can choose between all three types. if you've seen any kind of deformation in viewport or buggy behaviour with other shaders in your project, just use "shader render pass" to avoid it.

![Screenshot_2](https://user-images.githubusercontent.com/80382116/216994976-12026dde-6b1f-4007-99a8-cda883fc1144.png)
