# MealPlanner Legal Pages (`mealplanner-legal`)

This repository contains the official, public-facing legal documents and data safety compliance pages for the **MealPlanner** mobile application (Package: `com.mealplanner.meal_planner_app`).

## Purpose & Scope
* **Public Legal Compliance:** Hosts required public legal endpoints for the Google Play Store Console (Data Safety section disclosures, Privacy Policy URL, and Account Deletion URL).
* **GitHub Pages Hosting:** Designed specifically for free hosting via GitHub Pages with zero external dependencies, stylesheets, or CDN scripts.
* **Separation of Concerns:** **This repository contains ONLY public legal documents and static web assets. It does NOT contain the MealPlanner Flutter application source code, mobile codebase, backend server logic, or private business logic.**

## Hosted Documents
1. **[Legal Hub (`index.html`)](index.html):** Overview portal linking to all policy documents.
2. **[Privacy Policy (`privacy-policy.html`)](privacy-policy.html):** Complete privacy policy covering authentication, health/nutrition data, local & cloud storage, zero-advertising & zero-tracker architecture, and data protection practices.
3. **[Account & Data Deletion (`delete-account.html`)](delete-account.html):** Step-by-step instructions for in-app deletion (`Settings > Delete Account & Data`), guest mode device wiping, external deletion requests, and Google Play subscription cancellation guidelines.

## GitHub Pages Deployment Instructions
1. Create a public repository on GitHub named `mealplanner-legal`.
2. Push the contents of this repository to GitHub:
   ```bash
   git remote add origin https://github.com/<your-username>/mealplanner-legal.git
   git branch -M main
   git push -u origin main
   ```
3. In your GitHub repository, navigate to **Settings > Pages**.
4. Under **Build and deployment > Source**, select **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Once deployed, your public URLs will be:
   * **Privacy Policy URL:** `https://<your-username>.github.io/mealplanner-legal/privacy-policy.html`
   * **Account Deletion URL:** `https://<your-username>.github.io/mealplanner-legal/delete-account.html`
   * **Legal Hub URL:** `https://<your-username>.github.io/mealplanner-legal/index.html`

## Contact & Developer Inquiries
* **Developer Email:** [developer.spectralab@gmail.com](mailto:developer.spectralab@gmail.com)
