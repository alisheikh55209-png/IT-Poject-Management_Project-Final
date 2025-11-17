# Feature faraz projects

## Pull Request Title
**Feature: Add Faraz Projects Gallery with Activity/Session Section**

---

## Description

### Summary of changes made
This PR adds three DevOps/Infrastructure project cards to the TeamPortfolio Projects gallery, complete with detailed descriptions, technology tags, and custom SVG thumbnails. Additionally, an Activity/Session section has been integrated to provide transparency and visibility of team member contributions and discussions to the team lead and instructor.

### What changed and why

#### 1. **Projects Gallery Expansion** (TeamPortfolio/index.html)
Added three new project cards showcasing DevOps and Infrastructure expertise:

- **Scalable CI/CD Pipeline**
  - Description: Implemented a resilient CI/CD workflow using Docker, GitHub Actions, and Kubernetes for automated builds, parallel tests, and zero-downtime deployments of microservices.
  - Technologies: Docker, GitHub Actions, Kubernetes
  - Thumbnail: Custom SVG (faraz-ci-cd-realistic.svg)

- **Cloud Infrastructure Automation**
  - Description: Automated secure cloud provisioning with Terraform on AWS, including modular modules, IAM controls, and cost-aware layouts for staging and production.
  - Technologies: Terraform, AWS, Infrastructure as Code
  - Thumbnail: fashion-studio-website.jpg

- **Monitoring & Observability Stack**
  - Description: Built centralized observability using Prometheus, Grafana and Loki: dashboards, alerting rules, and log aggregation for faster incident response.
  - Technologies: Prometheus, Grafana, Logging
  - Thumbnail: nft-collection-website-cover-image.jpg

#### 2. **Activity/Session Section** (TeamPortfolio/index.html)
New section added to provide transparency:
- Displays project submission timestamps and updates
- Includes team conversation thread (Ali ↔ Faraz ↔ Teacher) for visibility
- Styled consistently with the rest of the site (responsive, dark mode compatible)

#### 3. **Styling** (TeamPortfolio/assets/css/style.css)
- Added `.activity-section` styles for responsive layout
- Included message formatting and meta information display
- Mobile-friendly design with proper spacing and colors

#### 4. **Custom Assets** (TeamPortfolio/assets/images/projects/)
Created high-fidelity SVG thumbnails:
- `faraz-ci-cd-realistic.svg` — Realistic pipeline visualization with Build → Test → Package → Deploy flow
- `faraz-terraform.svg` — Cloud infrastructure graphic
- `faraz-monitoring.svg` — Observability stack visualization

#### 5. **Documentation** (PROJECT_REPORT.md)
Updated with:
- Detailed session log with timestamps (Nov 17, 2025 14:30–15:00)
- Faraz's complete contributions breakdown
- Features implemented and testing procedures
- Update log tracking all changes made

---

## Type of change
- [x] New feature
- [ ] Bug fix
- [ ] Documentation
- [ ] Chore

---

## Related Issue
Fixes assignment: Faraz (Faraz Butt) — Projects gallery

---

## How to test
1. Open `TeamPortfolio/index.html` in a web browser
2. Scroll to the **Projects** section and verify three new project cards are displayed
3. Check that each card displays:
   - Project title
   - Description text
   - Technology tags
   - Project thumbnail image
4. Scroll to the **Activity & Session** section and verify:
   - Faraz's project submission is listed
   - Team conversation thread is visible and formatted correctly
5. Test responsive layout by resizing the browser or opening DevTools (F12) → device toolbar
6. Test dark mode by clicking the sun/moon icon in the navigation bar

---

## Checklist
- [x] I have read the CONTRIBUTING.md and followed the workflow
- [x] My code follows the repository style guide
- [x] I have reviewed my changes locally and tested the layout
- [x] I have added/updated documentation where necessary
- [x] I did not commit sensitive information (secrets, credentials)
- [x] All project images and assets are properly referenced and committed

---

## Notes for Reviewer
- All three project cards follow the same design pattern and styling as existing projects
- SVG thumbnails are scalable and responsive, ensuring consistency across devices
- Activity/Session section provides transparency for instructor grading
- Branch: `feature-faraz-projects`
- No breaking changes — fully backward compatible with existing layout

---

## Additional Context
This work is part of the IT Project Management course final submission. The projects represent realistic DevOps/Infrastructure engineering tasks and demonstrate proficiency in:
- CI/CD pipeline design and implementation
- Cloud infrastructure automation and provisioning
- System monitoring and observability practices

All commits follow the git workflow and are ready for merge into the main branch after review.
