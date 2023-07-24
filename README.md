# Espaloma-0.3.0-manuscript
This repository summarizes the repositories to create espaloma-0.3.0. More details can be found below.

## Related repositories
### 1. Download QCArchive datasets
This repository contains scripts used to download the QM data from [QCArchive](https://qcarchive.molssi.org/).
- https://github.com/choderalab/download-qca-datasets

### 2. Refitting Espaloma with energies and forces
This repository contains scripts to preprocess the QM data saved in HDF5 into dgl graphs, refit espaloma, and evaluate the refitted espaloma model.
- https://github.com/choderalab/refit-espaloma

### 3. Alchemical protein-ligand benchmark experiment using Perses
This repository contains scripts to run the alchemical protein-ligand free energy calculaiton using [Perses](https://github.com/choderalab/perses) using espaloma force field.
- https://github.com/choderalab/pl-benchmark-espaloma-experiment

## Contributors
- Kenichiro Takaba
- Iván Pulido
- Mike Henry
- Hugo MacDermott-Opeskin
- John D. Chodera
- Yuanqing Wang

## Citation
```
@misc{takaba2023espaloma030,
      title={Espaloma-0.3.0: Machine-learned molecular mechanics force field for the simulation of protein-ligand systems and beyond}, 
      author={Kenichiro Takaba and Iván Pulido and Mike Henry and Hugo MacDermott-Opeskin and John D. Chodera and Yuanqing Wang},
      year={2023},
      eprint={2307.07085},
      archivePrefix={arXiv},
      primaryClass={physics.chem-ph}
}
```

## License
[MIT license](https://opensource.org/licenses/MIT)