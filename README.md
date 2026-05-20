# chimahon-local-models

Prebuilt TFLite models and protobuf configs for the on-device Lens OCR engine used by Chimahon.

## Structure

```
screenai_models/   # TFLite models, protobuf configs, LM FSTs
```

## Release

Trigger the `Release Models` workflow manually with a version tag:

```bash
gh workflow run release-models.yml -f version=v1.0
```

Or use the GitHub UI: Actions → Release Models → Run workflow.
