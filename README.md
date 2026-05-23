# New API FG LAB Render Image

Public build wrapper for the FG LAB themed New API test deployment on Render.

The workflow clones `QuantumNous/new-api` at a pinned commit, applies the local FG LAB UI patch, adds the small homepage assets, and publishes:

`ghcr.io/nuannuandean-collab/new-api-fglab:latest`

No database credentials, API keys, or Render environment variables are stored in this repository.
