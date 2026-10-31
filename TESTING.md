# Verification record

Tested locally with Python 3.12, NumPy 2.3.5, SciPy 1.17.0 and (Project 1) scikit-learn 1.8.0. `check_data.py` and the starter/evaluation commands were run on CPU. Project 1 smoke test used five epochs; the distributed default uses thirty. This is a smoke test and numerical sanity check, not validation of a research finding. A hosted Colab session and GPU were not exercised.

The data are fixed files. Running `generate_data.py` regenerates them and may change compressed-file checksums because ZIP timestamps change. Compare array contents when checking regeneration. The stored `MANIFEST_SHA256.json` checks the bytes of the distributed files.
