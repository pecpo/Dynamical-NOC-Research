# Computer Architecture Project

This repository contains the implementation and necessary files for our Computer Architecture project. The repository is divided into two folders: `real-world` and `synthetic`.

## Folder Structure and File Placement

### Real-World Folder

1. **`x86-parsec-test-benchmark.py`**
   - **Path:** `./configs/example/gem5_library/x86-parsec-test-benchmarks.py`
   - Description: This script is used to test the Parsec benchmarks in gem5 with the customized NoC.

2. **`garnet_mesh.py`**
   - **Path:** `./src/python/gem5/components/cachehierarchies/ruby/topologies/garnet_mesh.py`
   - Description: This file defines the mesh-based NoC topology and incorporates details such as SERDES units.

3. **`mesi_two_level_cache_hierarchies.py`**
   - **Path:** `./src/python/gem5/components/cachehierarchies/ruby/mesi_two_level_cache_hierarchies.py`
   - Description: This file modifies the default cache hierarchy to work with the Garnet mesh topology.

---

### Synthetic Folder

1. **`Mesh_XY_NoC.py`**
   - **Path:** `./configs/topologies/Mesh_XY_NoC.py`
   - Description: This file defines a heterogeneous mesh topology with varying channel widths.

2. **`Mesh_XY_NoC_2.py`**
   - **Path:** `./configs/topologies/Mesh_XY_NoC_2.py`
   - Description: This file defines a heterogeneous mesh topology with varying router frequencies.

3. **`garnet_synth_traffic.py`**
   - **Path:** `./configs/example/garnet_synth_traffic.py`
   - Description: A synthetic traffic generator for testing NoC topologies.

---

## Usage Instructions

1. Clone the repository and place the files as specified in the paths above.
2. Follow the gem5 setup instructions to ensure the environment is configured correctly.
3. Run the benchmarks or synthetic tests using the provided scripts.

For additional details, refer to the project documentation or reach out to the contributors.

---

## Contributors

- [Tanmay Singhal]
- [Rohak Kansal]
- [Tejash Prasad]
