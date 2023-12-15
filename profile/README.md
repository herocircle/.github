# HeroCircle Project Overview
![Project Logo/Icon](https://assets-global.website-files.com/6057e010b2aa08f0ce7ece0b/6503cdb5071455e5c0b9dcb3_Group%20631404.png)
## Introduction
Welcome to the HeroCircle project repository! This project encompasses multiple frontend applications and a backend service, designed to deliver a comprehensive and robust experience for different user segments. Below you'll find detailed information about each component and relevant links.

### Frontend Applications
- **Main App**
  - **Staging**: [staging.herocircle.app](https://staging.herocircle.app/)
  - **Production**: [herocircle.app](https://herocircle.app/)
  - **Repository**: [Hero-NewFrontend](https://github.com/herocircle/Hero-NewFrontend)

- **Dashboard**
  - **Staging**: [dash-staging.herocircle.app](https://dash-staging.herocircle.app/)
  - **Production**: [dash.herocircle.app](https://dash.herocircle.app/login)
  - **Repository**: [Hero-Dashboard](https://github.com/herocircle/Hero-Dashboard)

- **B2B Dashboard**
  - **Staging**: [organizations-staging.herocircle.app](https://organizations-staging.herocircle.app/)
  - **Repository**: [B2B Dashboard](https://github.com/herocircle/b2b-dashboard)

### Backend Service
- **Staging**: [staging-api.herocircle.app](https://staging-api.herocircle.app/)
- **Production**: [api.herocircle.app](https://api.herocircle.app/)
- **Repository**: [hero-circle-api](https://github.com/herocircle/hero-circle-api)
- **Swagger Documentation**: [Swagger](https://staging-api.herocircle.app/swagger)
  - **Note**: For local backend setup, a vault token is required. Contact Wahib or the team for access.

### Landing Pages
- **Production (Webflow)**: [landing.herocircle.app](https://landing.herocircle.app/)
- **Staging**: [staging.herocircle.app](https://staging.herocircle.app/)

### Development Workflow
- **Linear**: Track all tickets at Hero Labs on Linear
- **Branch Naming**: Match branch names with ticket IDs (e.g., HER-853) for automatic tracking in Linear.

### Deployment
- **Staging**: Automated builds via GitHub Actions on main branch updates or pull request merges.
- **Production**: Manual trigger of GitHub Actions for builds.

### Hero Developer Commandments
1. **Client Use**: Always use our client; avoid direct endpoint usage.
2. **Component Nesting**: Avoid nesting components; keep the code modular.
3. **Code as Art**: Treat code writing as an art form for future maintainability.
4. **useEffect**: Use useEffect sparingly and only in rare cases.
5. **Common Components**: Reuse common components like loaders.
6. **Custom Hooks**: Open to using custom hooks post-review.

### Practical Knowledge
#### Client Generation:
1. Visit Swagger Editor.
2. Import the updated Swagger JSON.
3. Choose 'Generate Client' -> 'typescript-axios'.
4. Replace the generated models and endpoints in the frontend.

#### Reducing useEffect Usage:
Refer to TanStack Query documentation for elegant useQuery examples.
