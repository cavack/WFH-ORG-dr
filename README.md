# WaterfallHunter DR Vault

Private off-host recovery vault for WaterfallHunter.

This repository is not an application source repository. Its Git tree contains only the independently runnable restore harness. Production backup payloads are published only as immutable GitHub Release assets and must contain authenticated metadata plus encrypted chunks; plaintext production databases must never be committed or attached to a release.
