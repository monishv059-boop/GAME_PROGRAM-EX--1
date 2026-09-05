# GAME_PROGRAM-EX--1
Aim
To implement and demonstrate various material effects in Unreal Engine, including emissive, roughness, and metallic properties, using the Material Editor.

Procedure
Create a New Material:

Open Unreal Engine.
In the Content Browser, right-click and select Material.
Name it M_EffectsDemo.
Apply Base Color:

Open the material.
Add a Vector Parameter or Constant3Vector node and connect it to the Base Color input.
Add Emissive Effect:

Add a Multiply node.
Connect a Constant3Vector (for emissive color) and a Scalar Parameter (for intensity).
Connect the result to the Emissive Color input.
Control Roughness:

Add a Scalar Parameter node and connect it to the Roughness input.
Lower values = shinier surface, higher values = rougher surface.
Control Metallic Property:

Add a Scalar Parameter node and connect it to the Metallic input.
0 = non-metal, 1 = fully metallic.
Save and Apply Material:

Save the material.
Apply it to any mesh in the scene (like a sphere or cube) to preview the results.

Output:
<img width="1192" height="791" alt="image" src="https://github.com/user-attachments/assets/13f6050b-68f8-4f0c-ace1-26017ba214d0" />
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/5d04a1f5-fd3d-4911-b382-7a17a7a1d4dc" />

Result:
Successfully implemented a material in Unreal Engine showcasing:

Emissive glow using emissive color and intensity.
Variable surface roughness to simulate different textures.
Metallic appearance adjustment to reflect light like real-world metals.
This setup enables dynamic, realistic materials suitable for use in environments, characters, and VFX in Unreal Engine projects.
