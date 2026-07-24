# Generated Artifact Archive

The complete curated GTHL-Emo generated-output bundle is available in the public [v1.0.0 release](https://github.com/Mashary-Alrasheedy/GTHL-Emo/releases/tag/v1.0.0).

## Release asset

| Asset | Contents |
| --- | --- |
| `GTHL-Emo_reported_outputs_v1.0.0.zip` | Curated recorded outputs: configurations, results, predictions, tables, figures, logs, notebooks, scripts, and model checkpoints. |
| `SHA256SUMS.txt` | SHA-256 checksum for the artifact archive. |

Raw benchmark datasets are not redistributed. The archive is derived from the curated generated-output tree and excludes local system metadata, local absolute paths, and the internal bundle README.

## Download and verify

```bash
gh release download v1.0.0 \
  --repo Mashary-Alrasheedy/GTHL-Emo \
  --pattern 'GTHL-Emo_reported_outputs_v1.0.0.zip' \
  --pattern 'SHA256SUMS.txt' \
  --dir GTHL-Emo-v1.0.0

cd GTHL-Emo-v1.0.0
shasum -a 256 -c SHA256SUMS.txt
```

## Restore the output tree

```bash
mkdir -p reported_outputs
unzip GTHL-Emo_reported_outputs_v1.0.0.zip -d reported_outputs
```

The restored tree contains the recorded dataset-specific results, figures, tables, logs, configurations, tuning candidates, notebooks, scripts, and checkpoints.
