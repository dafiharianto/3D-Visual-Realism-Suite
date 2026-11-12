# 3D Visual Realism Suite (Grafika Komputer - Minggu 11)

Implementasi pipeline rendering 3D berbasis **Java 17+, LWJGL 3, JOML, dan Modern OpenGL (GLSL 330 core)** yang mencakup:
1. **Shading Models:** Phong vs Blinn-Phong Reflection Model
2. **Surface Interpolation:** Flat Shading vs Smooth Shading
3. **Hidden Surface Removal (HSR):** Z-Buffer Depth Test & Back-Face Culling
4. **Texture Mapping:** UV Mapping, Mipmapping, & Nearest/Bilinear Filtering
5. **Real-Time Shadows:** Two-Pass Shadow Mapping dengan Depth FBO & Slope-Scaled Bias

## Kontrol Interaktif
- `B` : Beralih antara Blinn-Phong dan Phong Shading
- `F` : Beralih antara Smooth dan Flat Shading
- `Z` : Mengaktifkan / menonaktifkan Z-Buffer Depth Test
- `C` : Mengaktifkan / menonaktifkan Back-Face Culling
- `T` : Mengaktifkan / menonaktifkan Texture Mapping
- `M` : Beralih mode filtering (`GL_LINEAR_MIPMAP_LINEAR` vs `GL_NEAREST`)
- `Q` / `E` : Menggeser posisi sumber cahaya
- `Tombol Panah` : Menggerakkan sudut pandang kameras