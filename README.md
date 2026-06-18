# AMANDLA / Safe-Hub Technology

Digital platforms, data systems and technology infrastructure supporting Safe-Hub’s mission to help young people and communities thrive.

## About Safe-Hub

Safe-Hub creates safe spaces where young people can access the care, resources, opportunities and support they need to grow, connect and achieve their goals.

The Safe-Hub model was first established in Khayelitsha, South Africa in 2007 by AMANDLA Social Enterprises, together with young people and community members. What began as a local response to the need for safe spaces to play and learn has grown into a global platform for youth and community development.

Today, Safe-Hub operates across multiple countries, including South Africa, Germany, the United States, India and Côte d’Ivoire, working with local partners to deliver community-based programmes that support young people, families and local ecosystems.

## Our Technology Purpose

This GitHub organisation exists to support the digital platforms, technical systems and software projects that help AMANDLA and Safe-Hub deliver impact at scale.

Our technology supports:

- Youth registration and onboarding
- Safe-Hub portal experiences
- Hub discovery and location services
- Programme participation and engagement
- Data collection and reporting
- Monitoring, evaluation and impact tracking
- Partner and operational workflows
- Secure, scalable and maintainable digital infrastructure

Technology is not the mission. Technology enables the mission.

Our goal is to build reliable, accessible and human-centred systems that help Safe-Hub teams serve young people and communities more effectively.

## Core Principles

### Young people first

Every technical decision should support better outcomes for young people. Systems must be simple, inclusive, accessible and designed around the real-world needs of the communities Safe-Hub serves.

### Safe, secure and trusted

We work with sensitive personal, programme and community data. Security, privacy, responsible access control and data protection are foundational requirements across all repositories and systems.

### Built for collaboration

Safe-Hub’s model is rooted in partnership. Our software should make it easier for internal teams, local hubs, implementation partners and technical contributors to work together clearly and effectively.

### Scalable and sustainable

Solutions should be maintainable, well-documented and designed to grow with Safe-Hub’s global footprint. We prefer clear architecture, simple operational patterns and practical engineering choices.

### Impact-driven

Our platforms should help teams understand participation, engagement, outcomes and impact. Data should be collected responsibly and used to improve programmes, not merely to produce reports.

## Key Digital Platforms

### Safe-Hub Portal

The Safe-Hub Portal is a youth-facing digital entry point that helps users register, explore hubs, find opportunities and become part of the Safe-Hub community.

The portal experience is designed around simple, positive calls to action:

- Join the Safe-Hub community
- Register quickly
- Find a nearby hub
- Connect, learn and grow
- Access opportunities designed with young people in mind

### Operational and Data Systems

Behind the public-facing platforms are systems that support day-to-day operations, programme delivery, reporting and impact measurement.

These may include:

- Administrative dashboards
- Registration and profile management
- Hub and programme management
- Attendance and participation tracking
- Data exports and reporting tools
- Integrations with third-party platforms
- Monitoring and analytics infrastructure

## Repository Standards

All repositories in this organisation should aim to include the following:

```text
README.md              Project overview, setup and usage
.env.example           Required environment variables without secrets
docs/                  Additional technical or product documentation
tests/                 Automated tests where applicable
.github/               GitHub workflows, issue templates and PR templates
```

A good project README should explain:

- What the project does
- Who it is for
- How to run it locally
- Required services, tools and environment variables
- Deployment notes
- Testing instructions
- Ownership and support contacts
- Any security or data handling considerations

## Development Workflow

Recommended workflow:

1. Create a feature branch from the default branch.
2. Make focused, reviewable changes.
3. Include clear commit messages.
4. Open a pull request with context, screenshots and testing notes where relevant.
5. Request review from the appropriate maintainer.
6. Merge only after review, successful checks and deployment readiness.

Example branch names:

```text
feature/youth-registration-flow
fix/hub-search-validation
chore/update-dependencies
docs/api-authentication
```

Example commit messages:

```text
feat: add youth registration form validation
fix: correct hub search empty-state message
docs: add local setup instructions
chore: update deployment workflow
```

## Security and Privacy

Repositories in this organisation may support systems that process personal information relating to young people, staff, partners and community members.

Contributors must not commit:

- Passwords
- API keys
- Access tokens
- Private certificates
- Production database dumps
- Personal information in test files
- Sensitive operational data
- Unredacted logs containing user information

Use environment variables and secure secret management for all credentials.

If you discover a vulnerability, exposed secret or data protection concern, do not open a public issue. Escalate it privately to the relevant technical owner or organisation administrator.

## Data Protection

Where systems collect or process personal information, projects should follow responsible data handling practices, including:

- Collecting only what is necessary
- Limiting access to authorised users
- Protecting data in transit and at rest where appropriate
- Keeping audit trails for sensitive actions where required
- Avoiding unnecessary duplication of personal data
- Using anonymised or synthetic data for development and testing
- Following applicable privacy and data protection requirements

## Accessibility

Safe-Hub platforms should be usable by the widest possible audience.

Where applicable, projects should consider:

- Mobile-first design
- Clear language
- Good colour contrast
- Keyboard navigation
- Screen reader support
- Simple forms and validation messages
- Low-bandwidth and lower-end device constraints

## Environments

Typical environments may include:

| Environment | Purpose |
|---|---|
| Local | Developer setup and testing |
| Development | Shared internal development environment |
| Staging | Pre-production testing and stakeholder review |
| Production | Live systems used by real users |

Production systems should be protected by appropriate access controls, monitoring, backups and deployment processes.

## Documentation Expectations

Documentation should be practical and kept close to the code.

Each repository should document:

- Local setup
- Environment variables
- Build commands
- Test commands
- Deployment process
- External integrations
- Known limitations
- Troubleshooting steps

Where possible, include examples.

## Contributing

This organisation is primarily for AMANDLA / Safe-Hub technology projects and approved collaborators.

Before contributing:

1. Confirm you have access to the correct repository.
2. Read the project README.
3. Check open issues and current pull requests.
4. Follow the repository’s development and review process.
5. Ask the project maintainer if anything is unclear.

## Useful Links

- Main website: https://safe-hub.org/
- About Safe-Hub: https://safe-hub.org/about-us/
- Safe-Hub Portal: https://portal-stage.safe-hub.online/

## Maintainers

This GitHub organisation is maintained by the AMANDLA / Safe-Hub technology team and approved technical partners.

For repository-specific questions, please refer to the maintainers listed in the relevant project README.

## Mission Reminder

Safe-Hub’s work is about creating spaces where young people can thrive.

Every line of code, every deployment, every dashboard and every integration should help make that work safer, stronger, simpler or more scalable.
