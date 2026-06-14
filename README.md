# 3P0D | EDUCATION | UNITY | Parallax Card Template

##  Project Overview
This Unity project serves as a template and a virtual showroom for a **3D Game Art course using Blender + Unity**. 
The goal is for each student to import, configure, and integrate their own custom 3D assets into a collective virtual card showroom. 
To ensure a seamless integration of everyone's work into the final build, **strict technical restrictions and guidelines must be followed**. 
Any asset that does not comply with the rules outlined below will be rejected until properly exported.


## Setup & Installation
1. **Clone the repository** to your local machine.
3. Open the project using the required **Unity version**.
4. Open the main showroom scene located in `Assets/Scenes/`.

## Integration Rules & Guidelines


#### 1. Prefab Creation and Hierarchy
* **Do Not Modify the Template Prefab:** Never edit the base prefab `P_0_template_card` directly. You would have to start over.
* **Create a Prefab Variant:** Right-click on `P_0_template_card` $\rightarrow$ **Create** $\rightarrow$ **Prefab Variant**.
* **Asset Placement:** All your custom 3D models, meshes, and visual elements must be placed inside the hierarchy under the `_ModelHolder` GameObject of your variant.

#### 2. Layer + Naming Conventions
* **Layer Assignment:** Every object placed under `_ModelHolder` **must** be set to the `Masked` layer. This ensures the parallax and masking effects render correctly.
* **Naming Convention:** Put your initials after each prefixes. 
  * *Example:* `P_StudentLetters_CardTheme` (Check the `Assets/Prefabs` folder for reference).
* Follow the naming convention below, see the project assets for examples:

| Asset | Prefix | 
| ---------------- | ---------------- |
| FBX Models   | 3d_  |
| Materials   | M_  |
| Textures   | T_  |
| Fonts  | FT_  |
| Shadergraphs   | SG_  |
| Prefab   | P_  |
| Prefab Variants  | Pv_  |
| Sprite (FX)  | 2d_FX_  |
| Sprite (FX)  | 2d_FX_  |

#### 3. Card Background + Datas
On the root GameObject of your Prefab Variant, locate the main card component script and fill out the following variables:
* **Background Color:** Choose and assign the background color that best fits your asset's art direction.
* **Student Name:** Enter your full name in the designated string variable for proper credits in the showroom.


## Licensing
This project is provided "as is" without warranty of any kind. You are free to use and modify it for educational purposes.
