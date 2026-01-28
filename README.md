# Linux Performance Triage Dataset

This repository contains a dataset of structured Linux performance telemetry
feature bundles collected under controlled workload scenarios.

## Contents
- `bundles/`: JSON files, one per run, containing extracted telemetry features
  and ground-truth bottleneck labels.

## Scenarios
Each bundle corresponds to one of the following scenarios:
- CPU contention
- I/O bottleneck
- Memory pressure

## Feature Extraction
Features are deterministically extracted from standard Linux tools
(e.g., mpstat, iostat, free, ps, vmstat).

## Usage
The dataset is intended for benchmarking performance diagnosis systems,
including heuristic and learning-based approaches.

## Citation

If you use this dataset in academic work, please cite the following paper:

> Omar Al-Mousa, et al.  
> *Assisting Linux Performance Diagnosis Using Large Language Models*, 2026.


### BibTeX
```bibtex
@article{nemrawi2026linuxllm,
  title     = {Assisting Linux Performance Diagnosis Using Large Language Models},
  @article{ --,
  title   = {Assisting Linux Performance Diagnosis Using Large Language Models},
  author  = {Al-Mousa, Omar and
             Al-Nemrawi, Mona and
             Al-Qudah, Ban and
             Masa'deh, Leen},
  year    = {2026}
}

  year      = {2026}
}


## License
MIT
