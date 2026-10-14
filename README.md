# Portfolio Website

A static portfolio website presenting selected university projects, technical skills, study interests, and contact links.

## Structure

- `index.html`: page content, inline CSS, navigation, and project descriptions.
- `assets/`: project imagery referenced by the page.

## Page sections

The page contains project cards for SafePaws Rescue, BigRig Movers, and a buffer-overflow security lab, followed by skills, about, and contact sections. It uses a responsive grid, anchor navigation, and images loaded on demand.

## Preview

Serve the repository with a local static web server and open `index.html`. No package manifest or build step is present in the inspected root.

## Content and verification

Project descriptions should distinguish individual contributions from group work and template or third-party components. Screenshots and code excerpts should be published only with the appropriate approval.

The BigRig source currently verifies Oracle SQL and JSON generation; no MongoDB implementation is included in that repository. SafePaws and security-lab descriptions have not been checked against their project sources in this review.

The security project's second image link currently targets a BigRig schema image instead of its security graphic. That link should be corrected before publication of an updated page.

This README describes the inspected source; it does not claim a completed accessibility audit or browser testing.
