# Demo Shader: Procedural

## GLSL (Shadertoy)

## GLSL Code
Some `glsl` code goes here
```glsl
shader_type canvas_item;

void vertex() {
    // Called for every vertex the material is visible on.
}

void fragment() {
    // Called for every pixel the material is visible on.
    // Create a wavy pattern based on UV coordinates and time
    float value = sin(UV.x * 50.0 + TIME) * cos(UV.y * 50.0 + TIME);
    // Normalize the value to 0.0–1.0 for grayscale
    value = (value + 1.0) * 0.6;
    // Output as grayscale with full opacity
    COLOR = vec4(value, value, value, 1.0);
} 
```


## Pytorch
Some `python` code goes here
``` py
import numpy as np
def sum():
    print('shader development doc')

```