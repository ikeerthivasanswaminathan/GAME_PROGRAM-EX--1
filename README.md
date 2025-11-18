# GAME PROGRAMMING - EX - 1

## EXP - 1 Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine

## Name : KEERTHIVASAN S
## Reg no : 212223220046

## Aim
To implement and demonstrate various material effects in Unreal Engine, including emissive, roughness, and metallic properties, using the Material Editor.

## Procedure

1. **Create a New Material:**
   - Open Unreal Engine.
   - In the Content Browser, right-click and select **Material**.
   - Name it `M_EffectsDemo`.

2. **Apply Base Color:**
   - Open the material.
   - Add a **Vector Parameter** or **Constant3Vector** node and connect it to the **Base Color** input.

3. **Add Emissive Effect:**
   - Add a **Multiply** node.
   - Connect a **Constant3Vector** (for emissive color) and a **Scalar Parameter** (for intensity).
   - Connect the result to the **Emissive Color** input.

4. **Control Roughness:**
   - Add a **Scalar Parameter** node and connect it to the **Roughness** input.
   - Lower values = shinier surface, higher values = rougher surface.

5. **Control Metallic Property:**
   - Add a **Scalar Parameter** node and connect it to the **Metallic** input.
   - 0 = non-metal, 1 = fully metallic.

6. **Save and Apply Material:**
   - Save the material.
   - Apply it to any mesh in the scene (like a sphere or cube) to preview the results.
  
     
## Output

<img width="375" height="422" alt="op1" src="https://github.com/user-attachments/assets/ec1b7c26-eb24-44c7-9231-7ea6459daa5c" />

<img width="1536" height="859" alt="op2" src="https://github.com/user-attachments/assets/0448d876-2266-4ae2-be13-183232a93dd5" />

## Result

Successfully implemented a material in Unreal Engine showcasing:
- Emissive glow using emissive color and intensity.
- Variable surface roughness to simulate different textures.
- Metallic appearance adjustment to reflect light like real-world metals.

This setup enables dynamic, realistic materials suitable for use in environments, characters, and VFX in Unreal Engine projects.
