# GTHL-Emo

Official code repository for **GTHL-Emo: Adaptive Imbalance-Aware and Correlation-Aligned Training for Arabic Multi-Label Emotion Detection**.

## Overview

GTHL-Emo combines transformer-based semantic encoding, adaptive hybrid loss weighting, correlation-aligned label dependency modeling, and graph-based structural learning. The public source tree contains the dataset-specific Colab-exported implementations for:

- SemEval-2018-Ec-Ar;
- SemEval-2025 Track A (Arq); and
- ExaAEC.

## Repository contents

| Path | Purpose |
| --- | --- |
| `SemEval-2018/` | SemEval-2018 implementation. |
| `SemEval-2025/` | SemEval-2025-Arq implementation. |
| `ExaAEC/` | ExaAEC implementation. |
| `requirements.txt` | Runtime dependencies used by the implementations. |
| `ARTIFACTS.md` | Index and restoration instructions for the generated-output release asset. |
| `CITATION.cff` | Machine-readable metadata for citing this software release. |

The implementations are exported from Colab notebooks and retain their dataset-specific configuration and output paths. Run them in a Colab or GPU-enabled environment after placing the appropriate dataset files in the locations described below.

## Installation

```bash
python -m pip install -r requirements.txt
```

The Python Graphviz package is listed as a dependency; rendering architecture diagrams additionally requires the Graphviz system executable.

## Dataset access

Raw benchmark datasets are not redistributed. Obtain them from their original sources and place the files expected by each implementation in its corresponding directory:

- `SemEval-2018/`: [SemEval-2018 Task 1](https://huggingface.co/datasets/SemEvalWorkshop/sem_eval_2018_task_1)
- `SemEval-2025/`: [SemEval-2025 Task 11](https://github.com/emotion-analysis-project/SemEval2025-Task11)
- `ExaAEC/`: [ExaAEC](https://github.com/exaco/exaaec)

Follow the original dataset licenses and citation requirements.

## Generated experiment outputs

The complete curated generated-output bundle is available in the public [GTHL-Emo v1.0.0 release](https://github.com/Mashary-Alrasheedy/GTHL-Emo/releases/tag/v1.0.0). It contains recorded configurations, results, predictions, tables, figures, logs, notebooks, and model checkpoints. Download and restore it using [ARTIFACTS.md](ARTIFACTS.md).

## Citation

If you use the method or software, cite the associated publication and the versioned repository. The repository citation metadata is provided in `CITATION.cff`.

Alrasheedy, M. N., Tiun, S., & Fauzi, F. (2026). *GTHL-Emo: Adaptive Imbalance-Aware and Correlation-Aligned Training for Arabic Multi-Label Emotion Detection*. Electronics, 15(6), 1169. https://doi.org/10.3390/electronics15061169
