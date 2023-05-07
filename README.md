# Godot4 Vignette Shader

## Shader with size parameter 500

![](Screenshots/Screenshot.png)

<img src="Screenshots/sp1.png" title="" alt="" width="406">

## Shader with size parameter 200

![](Screenshots/Screenshot2.png)

<img src="Screenshots/sp2.png" title="" alt="" width="406">

## In the code:

```c
uniform float size = 200.0;
```

You can also modify this parameter from gdscript:

```gdscript
self.material.set_shader_parameter("size", 300)
```

I have implemented it in one of my shaders (02_WhiteRectMouse) in this project --> https://github.com/TechnoLukas/Godot4-Shaders 
