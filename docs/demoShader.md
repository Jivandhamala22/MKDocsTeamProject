# Demo Shader: Gradient

## GLSL (Shadertoy)

### Code
    // glsl code
    void mainImage(out vec4 fragColor, in vec2 fragCoord) {
        vec2 uv = fragCoord / iResolution.xy;
        fragColor = vec4(uv.x, uv.y, 0.0, 1.0);
    } 0