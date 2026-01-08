---
hide:
  - toc
---
# Security Overview

The project is for educational purposes. These are the instructions for the upcoming demonstration. It requires about 6–8 hours of work to integrate, run, and accomplish these steps with our current tooling.

## Setup

- [ ] Fork the [insecure-banking](https://github.com/mighty-muffin/insecure-banking) with all branches
- [ ] Read the project documentation
- [ ] Verify everything works
- [ ] Run `make all` from the `Makefile`, if available

## Scenario

Please take a look at each of the following six (6) scenario.

1. [SDLC Bad Practices](security/scenario-1.md)
2. [Dependency Vulnerabilities](security/scenario-2.md)
3. [Exemption & Waivers](security/scenario-3.md)
4. [Code Vulnerabilities](security/scenario-4.md)
5. [Container Vulnerabilities](security/scenario-5.md)
6. [SBOM Generation](security/scenario-6.md)

If required use the [Branches Pipeline](../pipeline/branches.md) to implement any workflow steps.

## And everything in between

- Showcases whatever you wish to highlight during the demonstration
- Highlights **shift-left**[^1] capabilities has much as possible recommended
- Allocates the available time to scenario you can present; if you cannot demonstrate a scenario
- Ignores all **hardcoded** or **leaked credentials**; [GitGuardian](https://github.com/GitGuardian/ggshield) will take care of them

[^1]: [Shift-left testing](https://en.wikipedia.org/wiki/Shift-left_testing)
