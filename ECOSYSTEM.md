# Ecosistema NVIDIA Warp

Repositorios clonados por separado. Cada checkout es shallow y queda en HEAD detached, fijado al SHA completo de la tabla.

| Grupo | Carpeta | Repositorio | Commit fijado |
| --- | --- | --- | --- |
| Geometry | `Geometry/CGAL` | https://github.com/victorjosegarcia888-cpu/cgal | `9484faba7d626ca04520ff80187ef51a2becb1b1` |
| Geometry | `Geometry/EBGeometry` | https://github.com/victorjosegarcia888-cpu/EBGeometry | `26469fc24f95967b682f25b9646e59b753dc7690` |
| Plugins | `Plugins/cae-openusd-plugins` | https://github.com/victorjosegarcia888-cpu/cae-openusd-plugins | `463551d45f0b73ee5aa669b0c07aa3690c339eed` |
| GPU | `GPU/Warp` | https://github.com/victorjosegarcia888-cpu/NVIDIAwarpIII | `f159ecdff60099f985ed52c19e79b01879680823` |
| GPU | `GPU/FVDB` | https://github.com/victorjosegarcia888-cpu/fvdb-core | `63c4565e40c946bd43dd92a3fd1b975750be5dde` |
| Visualization | `Visualization/OpenEXR` | https://github.com/victorjosegarcia888-cpu/openexr | `12fc65c264a8a624f423fec68d0b085a4ddd0d48` |
| Visualization | `Visualization/OpenUSD` | https://github.com/victorjosegarcia888-cpu/OpenUSD | `ee47c679abde5b467a7b6a41f3b2285564a4222e` |
| Visualization | `Visualization/Kit-CAE` | https://github.com/victorjosegarcia888-cpu/kit-cae | `38b198b84b9e958b1ecd7717e49fe04463878d5b` |
| Visualization | `Visualization/RTXPT` | https://github.com/victorjosegarcia888-cpu/RTXPT | `f08d1c739071e0faad0c7c274d861124c511abab` |
| Visualization | `Visualization/OpenShadingLanguage` | https://github.com/victorjosegarcia888-cpu/OpenShadingLanguage | `8c9c1519afc3fddaedc78b421d485afd7275af44` |
| Visualization | `Visualization/OpenFX` | https://github.com/victorjosegarcia888-cpu/openfx | `e40728885390ec16276d11e00025de9b4282060c` |
| Dependencies / Formats | `Dependencies/Formats/assimp` | https://github.com/victorjosegarcia888-cpu/assimp | `ab76f8df17f8307c7a2dd07c97aae2e972bb5180` |
| Dependencies / Math | `Dependencies/Math/Imath` | https://github.com/victorjosegarcia888-cpu/Imath | `5b39e4699b028b3bdd5b9712be2fdc24ab0efcb1` |
| Simulation | `Simulation/AMReX-Hydro` | https://github.com/victorjosegarcia888-cpu/AMReX-Hydro | `a153304acd787205b170b0f7fd8284627e076056` |

## Notas

- OpenEXR está fijado en la versión 4.0.0. Su configuración busca Imath 3.1 o superior; el Imath fijado aquí declara la versión 3.2.0. Imath se mantiene una sola vez en `Dependencies/Math/Imath` y no se copia dentro de OpenEXR.
- Warp contiene un objeto LFS ausente en el remoto (`docs/img/examples/core_dem.png`, respuesta 404). El checkout se completó omitiendo el smudge de LFS; ese archivo puede no estar disponible en `GPU/Warp`.
