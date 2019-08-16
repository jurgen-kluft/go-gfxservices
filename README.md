# HTTP Service

## Graphics Services

Note: A Cache to store many of the requests

A request is using JSON format to describe the JOB.

- LOD (InstaLOD, Simplygon)
  - Config + glTF model
  - Receive glTF models
- Texture Compilation
  - Config
    - Console (PS4, Xbox, Switch)
    - SDK Version
    - Generate Mips
    - Destination Texture Format
  - Source Texture
    - JPG / TGA / PNG / BMP
  - Receive: Binary BLOBs
- Shader Compilation
  - Config
    - Console (PS4, Xbox, Switch)
    - SDK Version
    - Generate DEBUG
  - Source Shader
    - HLSL / GLSL
- Test
