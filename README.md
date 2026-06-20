# spirulae-splat-colab

This repository builds pre-compiled wheels for `spirulae-splat` targeting Google Colab.

**Note:** This repository does not contain `spirulae-splat` source code directly. Instead, the GitHub Actions workflow will:
1. Clone the upstream master repository from `harry7557558/spirulae-splat`.
2. Apply Colab compatibility patches (found in the `patches/` folder).
3. Build the wheels and publish them to GitHub Releases.

This allows you to easily install the pre-compiled, optimized wheels on Google Colab without needing to wait for a full compilation from source.
