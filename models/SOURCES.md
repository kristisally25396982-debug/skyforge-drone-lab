# sf-x500.glb

- Upstream: [PX4/PX4-gazebo-models](https://github.com/PX4/PX4-gazebo-models) (`models/x500_base`, `models/gimbal`)
- License: BSD-3-Clause. Copyright (c) 2022, Rudis Laboratories. Copyright (c) 2022, PX4 Autopilot for Drones. Full text: [LICENSE.txt](./LICENSE.txt)
- This build does not use the PX4 or Rudis names as a product brand. The on-screen name is the fictional SF-X500.
- Decimation used [meshoptimizer](https://github.com/zeux/meshoptimizer) (MIT) through a one-off gltf-transform script. meshoptimizer is not a runtime dependency.
- Runtime load path: `GLTFLoader` (three.js, MIT). The file is plain glTF binary, about 58k triangles, under 1 MB. No Draco decoder.
- Node names are the lab part ids. `propeller_*` nodes carry `extras.spinDir`.
