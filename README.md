# RIYUN Golf Static Site

This repository contains the complete static site for riyun-golf.com.

## Cloudflare Pages setup
1. Create a NEW Cloudflare Pages project connected to this GitHub repository.
2. Framework preset: None; build command: leave empty; output directory: / (repository root).
3. Check the new Pages preview URL before changing any production domain.
4. After verification, detach the domain from the old direct-upload project and attach it to the new project.

The GitHub Actions workflow only validates the files; Cloudflare Pages performs deployment after its Git integration is configured.
Do not place confidential M&A project data in this public repository.
