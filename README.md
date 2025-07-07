# Tornado VFX  
A realistic tornado effect recreated using the Niagara system in Unreal Engine.

---

## Final Result  

<p align="left">
  <img src="https://github.com/RafaelColpani/UE5-Tornado/blob/main/img/finalRender.gif" width="45%" />
   
  <img src="https://github.com/RafaelColpani/UE5-Tornado/blob/main/img/lightningRender.gif" width="45%" />
</p>


---

## How It Was Made

The main tornado was created using the **fluid simulation system** to replicate smoke behavior. This approach allows the effect to interact more naturally with ambient lighting, enhancing realism and depth.

 <img src="https://github.com/RafaelColpani/UE5-Tornado/blob/main/img/lightRender.gif" width="45%" />

Additional elements were added to push the realism further, including:

- Smoke trails  
- Dust particles at ground level  
- Flying debris and objects 

Each component contributes to a more immersive and physically plausible tornado effect.

---

## Installation

1. Make sure **Unreal Engine 5.6.0** is installed  
2. Download or clone the repository
3. Open the project folder:
   ```
   UE5_Tornado/
   ```
4. Double-click the `UE5_Tornado.uproject` file to launch the project

---

## Important Notes

**Performance Warning**  
This VFX is a **real-time simulation**, which means it is **not optimized** for use in a final game production. The performance cost may be too high for real-time gameplay.

For optimized, production-ready results, it is recommended to bake the simulation into a `.VDB` file using tools such as:

- [Houdini](https://www.sidefx.com/products/houdini/)  
- [Embergen](https://jangafx.com/software/embergen/)

These tools allow for complex volumetric simulations to be exported and rendered more efficiently inside game engines.
