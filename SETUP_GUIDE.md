# How to Setup Your Modern GitHub Organization Profile

This guide explains how to publish the **EyesOn SafeTech** profile on GitHub in under 2 minutes.

---

### Option 1: GitHub Organization Profile (Recommended)
If your GitHub account is an **Organization** (e.g. `github.com/EyesOnSafeTech`):

1. On GitHub, create a **public repository** named `.github`.
2. Inside that repository, create a folder named `profile`.
3. Upload:
   - The `README.md` file into `.github/profile/README.md`.
   - The `assets/` folder into `.github/profile/assets/`.
4. Done! When anyone visits `https://github.com/EyesOnSafeTech`, this modern portfolio will be displayed on your organization's homepage.

---

### Option 2: Company Account / Special Profile Repository
If you are using a standard GitHub account or want the profile in a dedicated showcase repo:

1. Create a public repository named exactly the same as your GitHub username/organization (e.g. `eyeson-safetech`).
2. Upload the `README.md` and the `assets/` folder directly to the root of that repository.
3. Commit and push.

---

### Assets Included in `assets/`:
- `hero-banner.svg`: 1200×420 px glowing cyber lattice header banner with genuine logo.
- `architecture-workflow.svg`: 1100×280 px 4-stage sovereign engineering pipeline.
- `stats-banner.svg`: 1100×140 px key performance metrics and SLAs.
- `capability-product.svg`: Product engineering competency card.
- `capability-security.svg`: Embedded cybersecurity competency card.
- `capability-velocity.svg`: Execution velocity competency card.
- `macbook-soc-dashboard.png`: High-res SOC dashboard mockup.
- `executive-desk-laydown.png`: Photorealistic corporate collateral laydown.
- `eyeson-logo-inverted.svg`: Official brand logo vector.
- `eyeson-shield-mark.svg`: Official shield emblem vector.
- `eyeson-security-seal.svg`: Official cryptographic security seal.

All image paths in `README.md` use clean relative paths (`./assets/...`) so they render automatically both online on GitHub and locally in any markdown viewer.
