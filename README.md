# YAABSA golden baselines

This repository stores the PNG reference images used by YAABSA's Flutter golden tests. The main repository mounts it at `test/ui/goldens/baselines/` so image blobs stay separate from application source.

The test definitions remain in YAABSA. To review and update snapshots, run:

```sh
flutter test --no-pub --concurrency=1 test/ui/goldens/components_golden_test.dart --update-goldens
```

Inspect every changed image before committing the corresponding update to this repository. The main YAABSA repository records the selected submodule commit.
