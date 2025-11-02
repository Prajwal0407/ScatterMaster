# **ScatterMaster**
A Blender add-on that scatters selected meshes across any surface with per-source weight, random rotation, scale, and normal alignment, creating a new collection for each scatter batch.


# ✨ Features

✅ Scatter meshes over any target mesh surface

✅ Weighted distribution between multiple source objects

✅ Randomized rotation and scale (per-axis)

✅ Optional surface normal alignment

✅ Configurable offset and jitter

✅ Automatically creates unique scatter collections

✅ Clear Latest Scatter deletes only the newest batch

✅ Per-source Weight / Scale / Rotation multipliers

# 🧩 Installation

**Follow these steps to install ScatterMaster in Blender:**

**1. Download the Add-on**
Click "Code → Download ZIP" on this repository,
or download the latest release from the Releases section.

**2. Install in Blender**
Open Blender and go to:
Edit → Preferences → Add-ons
Click "Install..." and select the downloaded .zip file.
Enable "ScatterMaster" from the add-ons list.

**3. Access the Tool**
Open the 3D Viewport.
Press N to open the Sidebar.
Go to the ScatterMaster tab.

# ⚙️ How to Use

**Step 1 — Add Source Meshes**
Select one or more meshes you want to scatter.
In the ScatterMaster panel, click Add Selected.
For each source, you can adjust:
• Weight – how frequently it appears
• Scale Mult – multiplies the random scale
• Rot Mult – multiplies the random rotation

**Step 2 — Choose Target Surface**
Select the mesh surface where you want to scatter (it must be active).
The tool supports any mesh type — quads, tris, or ngons.

**Step 3 — Adjust Scatter Settings**
• Instance Count – number of objects to scatter
• Offset / Offset Jitter – controls distance from the surface
• Align with Normal – orients scattered meshes to the surface
  You can also customize:
• Scale Range (X, Y, Z) – min/max scale per axis
• Rotation Range (X, Y, Z) – random rotation limits in radians

**Step 4 — Scatter**
• Click Scatter Meshes.
• ScatterMaster will create a new collection automatically
• Each scatter is separate, organized, and non-destructive.

**Step 5 — Clear the Latest Scatter**
• Click Clear Latest Scatter to remove only the most recent scatter collection.
  Previous scatters will remain untouched.

# 🧮 UI Overview

| **Section**                     | **Description**                                                                                        |
| --------------------------- | -------------------------------------------------------------------------------------------------- |
| 🎛 **Scatter Sources**      | Add or clear meshes as scatter sources. Adjust per-source weight, scale, and rotation multipliers. |
| 🎲 **Weight Randomization** | Randomly assign weights between your defined min/max range.                                        |
| ⚙️ **Scatter Settings**     | Control count, offset, jitter, and normal alignment.                                               |
| 📏 **Scale Range**          | Define per-axis random scaling limits.                                                             |
| 🔄 **Rotation Range**       | Define random rotation angles (in radians) for each axis.                                          |
| 🧹 **Actions**              | Scatter or clear instances easily.                                                                 |



# 📜 License

This project is licensed under the MIT License — free to use, modify, and distribute.

# 👨‍💻 Author
**Prajwal Mohite**

Technical Artist
