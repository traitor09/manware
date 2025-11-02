# ✨ Vision: MANWARE - The Integrated CI/CD Co-Pilot

The **MANWARE VS Code Extension** is the future of web deployment. It transcends simple file transfer, transforming your Integrated Development Environment (IDE) into an intelligent control center for the entire continuous integration and continuous deployment (CI/CD) pipeline.

This product is designed to manage the complexities of modern web projects—from single-page applications to Jamstack sites—and enable true **one-click, multi-stage, multi-platform deployment** directly from the editor.

## Why MANWARE is a High-Impact Product

It offers **professionalism, velocity, and resilience** by solving the fragmentation and complexity of modern deployment workflows.

### Core High-Value Features

| **Intelligent Configuration** | **Zero-Config Smart Deployment:** 
Automatically detects popular frameworks (React, Next.js, Vue, Hugo, Gatsby) and hosting platforms (GitHub Pages, Vercel, Netlify, Cloudflare Pages) to instantly generate and suggest the optimal deployment pipeline configuration (e.g., GitHub Actions YAML). 
**Accelerated Setup:** Eliminates hours spent debugging complex build scripts and manual configuration. Projects are deployable in seconds. 

| **Advanced Previews** | **IDE-Native Deploy Previews:** For every branch or pull request, Atlas Deploy generates a secure preview URL and embeds a sharable link and status directly within the VS Code Source Control view. 
 **Instant Collaboration & QA:** Developers and stakeholders can review live code changes without merging. This massively shortens the QA and feedback loop, boosting development velocity. 

| **Operational Visibility** | **Live CI/CD Dashboard:** Streams real-time build and deployment logs from the chosen host (e.g., GitHub Actions, Vercel console) directly into a dedicated VS Code panel, with immediate visual cues for errors. 
 **Rapid Troubleshooting:** Developers diagnose and fix failed deployments without leaving the IDE or switching contexts, ensuring maximum focus and efficiency. 

| **Production Safety** | **One-Click Atomic Rollbacks:** Presents a history of successful production deployments and enables instant, atomic rollback to any previous version. 
 **Resilience & Reliability:** Provides a safety net for immediate recovery from critical production bugs, minimizing downtime and risk. 

| **Secure Workflow** | **Integrated Environment Management:** Offers a secure interface within VS Code to manage and inject environment variables (secrets) specific to development, staging, and production stages for all supported hosts. 
 **Best Practice Enforcement:** Encourages proper handling of secrets and ensures environment parity across all stages, essential for professional-grade applications. 

## The Future: A Complete Deployment Lifecycle in Your IDE

MANWARE moves beyond simple convenience to become an indispensable tool for every developer seeking to manage the full software delivery lifecycle, all from the comfort and control of the Visual Studio Code editor.
## Deploy to GitHub Pages

The current PoC lets you quickly deploy your static web page (Jekyll or HTML) to GitHub Pages without leaving your IDE.

GitHub Pages is a static site hosting service that takes HTML, CSS, and JavaScript files straight from a repository on GitHub, optionally runs the files through a build process, and publishes a website. 

- This extension will only trigger a build for websites built with HTML, CSS, and JavaScript. Frameworks such as React, Vue, or Angular.
- GitHub Pages will use Jekyll to build your site by default.
- GitHub Pages does not support websites built with server-side languages such as PHP, Ruby, or Python. 

<p align="center">
  <img src="https://user-images.githubusercontent.com/22990146/158666441-bdab76ba-b634-4eb6-926a-ce2da3898f01.gif"/>
</p>
