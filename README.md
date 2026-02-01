# Schaefer2018 and Tian2020 Atlases Pack

This repository contains a BIDS-compatible atlas pack that combines the Schaefer2018 and Tian2020 atlases.

## Atlases

This pack includes the following atlases:

*   **Schaefer2018**: A local-global parcellation of the human cerebral cortex from intrinsic functional connectivity MRI.
*   **Tian2020**: A topographic organization of the human subcortex unveiled with functional connectivity gradients.

## File Structure

The atlases are organized into directories based on the number of parcels and the sub-cortical atlas scale. The directory structure is as follows:

```
Schaefer2018N<num_parcels>n7Tian2020S<scale>/
├── atlas-Schaefer2018N<num_parcels>n7Tian2020S<scale>_dseg.tsv
└── atlas-Schaefer2018N<num_parcels>n7Tian2020S<scale>_space-MNI152NLin2009cAsym_res-01_dseg.nii.gz
```

Where `<num_parcels>` is the number of parcels in the Schaefer2018 atlas (100, 200, 300, 400, 500, 600, 700, 800, 900, 1000) and `<scale>` is the scale of the Tian2020 sub-cortical atlas (1, 2, 3, 4).

## How to Use

These atlases can be used with any BIDS-compatible tool that supports atlas-based analysis. The `.tsv` file contains the region names and the `.nii.gz` file contains the atlas image.

## Citation

If you use these atlases in your research, please cite the original publications:

*   Schaefer, A., Kong, R., Gordon, E. M., Laumann, T. O., Zuo, X.-N., Holmes, A. J., Eickhoff, S. B., & Yeo, B. T. T. (2018). Local-Global Parcellation of the Human Cerebral Cortex from Intrinsic Functional Connectivity MRI. Cerebral Cortex, 28(9), 3095–3114. https://doi.org/10.1093/cercor/bhx179
*   Tian, Y., Margulies, D. S., Breakspear, M., & Zalesky, A. (2020). Topographic organization of the human subcortex unveiled with functional connectivity gradients. Nature Neuroscience, 23(11), 1421–1432. https://doi.org/10.1038/s41593-020-00711-6

