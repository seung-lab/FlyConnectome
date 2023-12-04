# FlyWire data access

This repository contains tutorials demonstraiting how to programmatically access the FlyWire connectome data. This [video of a workshop](https://www.youtube.com/watch?v=B5EeqVlOqjk) walks through these notebooks.

## Volumetric data and meshes

[Tutorial](https://github.com/seung-lab/FlyConnectome/blob/main/CAVE%20tutorial.ipynb)

The EM and segmentation datasets are too large for conventional downloads. They can be accessed via cloudvolume, a tool that faciliates a numpy-like interface to the data for subvolume reading. Please reach out to the Seung Lab if you need a copy of entire volumetric dataset (e.g. to train machine learning models) or want access to a higher resolution (4, 4, 40 nm) EM dataset.

Triangulated meshes are available for all segments in the datasets (proofread and unproofread) and can be download on a per-segment basis.

## Connectome annotations and queries

[Tutorial](https://github.com/seung-lab/FlyConnectome/blob/main/CAVE%20tutorial.ipynb)

[CAVE](https://www.biorxiv.org/content/10.1101/2023.07.26.550598v1) is the software infrastructure used to host the FlyWire dataset and the primary access point for programmatic queries. Through CAVE synaptic connections and annotations can be queried.

[Navis](https://navis.readthedocs.io/en/latest/source/other_libraries.html), [natverse](https://natverse.org/)(R), and [fafbseg](https://fafbseg-py.readthedocs.io/en/latest/index.html) also facilitate programmatic access to the connectome data. 

## Bulk download

Most of the connectome data can be downloaded in bulk from [Codex](https://codex.flywire.ai/api/download).

## Non-programmatic acces

Several tools facilitate non-programmatic access to the same underlying data. The primary portal is [Codex](https://codex.flywire.ai/). Other portals include [braincircuits.io](https://braincircuits.io/datasets) and [Catmaid spaces](https://fafb-flywire.catmaid.org/).
