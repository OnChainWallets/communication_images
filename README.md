# OnchainWallets Communication Assets Repository

Welcome to the OnchainWallets Assets Repository. This repository contains logos, email images, and third-party illustrations used for OnchainWallets projects.

# Instructions for Updating Attributions and Adding New Assets

These instructions guide developers on updating attributions and adding new assets to the OnchainWallets Assets Repository.

## Steps

1. **Add New Assets**:
   - For OnchainWallets assets: Place in `onchain/` (e.g., `onchain/new-logo.png`).
   - For third-party assets: Create/update subfolder in `third-party/` (e.g., `third-party/storyset/` or new `third-party/freepik/`).
   - Rename with source prefix, e.g., `st_new-hero.svg` for Storyset in `third-party/storyset/`.

2. **Update `attributions.md`**:
   - Edit `attributions.md` in GitHub.
   - For new generic source (e.g., Storyset): Add/update bullet in “Generic Attributions”:
     ```markdown
     - **Storyset Images**: Files with the prefix `st_` (e.g., `third-party/storyset/st_new-hero.svg`) are sourced from Storyset (https://storyset.com/).
       - **Attribution**: Credit as "Illustration by Storyset (https://storyset.com/)" unless using Flaticon Premium.
       - Users must follow Storyset’s Terms of Use (https://storyset.com/terms). OnchainWallets is not liable for misuse.
     ```
   - For specific assets (e.g., editorial-use): Add to “Specific Asset Attributions”:
     ```markdown
     - **third-party/storyset/st_new-editorial.svg**:
       - Source: Storyset (https://storyset.com/illustration/new-editorial)
       - Attribution: Illustration by Storyset
     ```
   - Update “Last verified” to today’s date (e.g., September 16, 2025).
   - Commit with message like “Add attributions for new assets”.

3. **Verify Related Files**:
   - Check `USAGE.md` references `attributions.md`.
   - Update `README.md` if new sources need mentioning (e.g., add example subfolder).

## Notes
- Verify provider terms (e.g., https://storyset.com/terms) before adding.
- For high-stakes use, consult a lawyer.

## Repository Structure
- **`onchain/`**: Contains proprietary logos and email images created by OnchainWallets. These are protected by copyright and subject to the usage policy outlined in `USAGE.md`.
- **`third-party/`**: Contains third-party images organized by source in subfolders (e.g., `third-party/storyset/` for Storyset images). Files in these subfolders, such as those with a `st_` prefix (e.g., `st_hero-illustration.svg`), are subject to their respective provider’s terms and attribution requirements, detailed in `attributions.md`.

## Usage Policy
All assets in this repository are subject to specific usage terms:
- **OnchainWallets Assets** (in `onchain/`): These are proprietary and may only be used for non-commercial purposes with attribution (e.g., "Logo courtesy of OnchainWallets"). Commercial use or modifications require explicit permission. See `USAGE.md` for full details.
- **Third-Party Assets** (in `third-party/`): These are governed by the original provider’s terms (e.g., Storyset’s Terms of Use: https://storyset.com/terms). You are responsible for complying with these terms, including attribution requirements. See `attributions.md` for details.

## Attributions
Third-party assets, such as those in the `third-party/` folder, require attribution unless otherwise specified. For example: "Illustration by Storyset (https://storyset.com/)". Full attribution details and source links are provided in `attributions.md`.

## How to Use This Repository
1. **Review Usage Terms**: Before using any assets, read `USAGE.md` for OnchainWallets’ proprietary assets and `attributions.md` for third-party assets.
2. **Comply with Terms**: Ensure your use aligns with the terms for each asset type. For third-party assets, verify the provider’s latest terms (e.g., Storyset’s Terms of Use).
3. **Provide Attribution**: Include required attributions for both OnchainWallets assets (in `onchain/`) and third-party assets (in `third-party/`) in your project’s credits, README, or website footer.
4. **Contact for Permissions**: For commercial use or modifications of OnchainWallets assets, contact onchain@onchainwallets.com.

## Disclaimer
OnchainWallets is not liable for misuse of any assets. Unauthorized use of proprietary or third-party assets may result in legal action from OnchainWallets or the respective provider (e.g., Storyset/Freepik).
