# PML-ED raw datasets

Original filenames and file contents are preserved from the supplied 数据集.zip. This repository contains only data/raw, extracted from the two original-data RAR archives.

| Directory | Contents | Files |
|---|---|---:|
| data/raw/arff | 原始多标签数据集.rar: original multi-label ARFF datasets | 20 |
| data/raw/mat | zhang_mat.rar: original MAT datasets and associated TXT files | 12 |

The 26 processed MAT files from 处理后的数据集.rar are excluded. The six original MAT datasets retain their supplied candidate labels and ground-truth labels. These candidate labels belong to the original partial multi-label benchmarks; see the accompanying TXT descriptions for their collection methods and references.

Total: 26 base datasets, 32 data/documentation files, approximately 225 MiB. Every individual raw file is smaller than 100 MiB.

```bash
git clone https://github.com/suoyifan4/PML-ED_data.git
```

See MANIFEST.csv for file sizes and SHA-256 checksums. Dataset sources and references are included in the accompanying TXT files where supplied. This repository does not assign a new license to the datasets.
