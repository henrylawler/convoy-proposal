# Convoy Capital Partners — Acquisitions Intelligence

## Project Overview
A static HTML page for Convoy Capital Partners, an Atlanta-based CRE (Commercial Real Estate) investment firm. The page serves as an acquisitions intelligence document prepared by LeveeTech LLC, outlining the firm's profile, capabilities, technology stack, and system architecture.

## Architecture
- **Type**: Pure static HTML site (single file)
- **No build system, no dependencies, no backend**
- **Server**: Python's built-in `http.server` on port 5000

## Project Structure
```
index.html    # Single-page static site (all CSS inline)
```

## Running the Project
The workflow runs:
```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Deployment
Configured as a **static** deployment with `publicDir: "."`.
