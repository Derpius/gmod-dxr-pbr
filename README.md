# GModDXR PBR Textures
PBR textures for GModDXR and any other project that may need them.  

All MRAO textures are in the format R - Ambient Occlusion (currently unused), G - Roughness, B - Metalness.  
For ease of loading these are the name of the diffuse texture with `_mrao` appended.  

Emission maps store the colour of the emission at a point, with black being no emission.  
These have the name of the diffuse plus the suffix `_emission`.  

Normal maps are currently not planned, but I may work on them after a large batch of MRAOs are done.  

Additionally transmission maps will have the suffix `_transmission`.  
