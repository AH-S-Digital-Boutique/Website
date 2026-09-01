# AH-S™ Website

> **Private production infrastructure for ASTON H-S Ltd.**
>
> **Unauthorised access, use, reproduction, redistribution or modification is prohibited.**

This repository contains the source code, architecture, assets, components, systems and supporting infrastructure used to operate the **AH-S™ Web Solutions Agency** website and associated digital experiences.

This is **proprietary software and intellectual property belonging to ASTON H-S Ltd.**

It is not an open-source project.

It is not a template.

It is not a public code library.

It is not available for reuse.

---

## ⚠️ ACCESS RESTRICTION

**AUTHORISED PERSONNEL ONLY.**

Access to this repository is granted solely at the discretion of **ASTON H-S Ltd.**

By accessing this repository, you acknowledge that its contents may contain confidential, proprietary and commercially sensitive information.

You must not, without prior written authorisation from ASTON H-S Ltd.:

* copy any part of this repository
* reproduce its source code
* redistribute its contents
* publish its contents elsewhere
* create derivative works
* reuse components, systems or assets
* disclose repository contents to third parties
* use the code or architecture for another business
* use the repository as a template for client or personal projects
* reverse engineer, extract or repurpose proprietary systems

**Public visibility of the deployed website does not grant permission to access, copy or reuse its underlying source code.**

---

## INTELLECTUAL PROPERTY

All original code, architecture, component systems, design systems, interfaces, written content, graphics, animations, configuration, tooling and other original materials contained within this repository are proprietary to **ASTON H-S Ltd.**, unless expressly identified otherwise.

Third-party dependencies remain subject to their respective licences.

Nothing in this repository grants any licence, assignment or other right to use AH-S™ intellectual property.

**Viewing does not equal ownership.**

**Access does not equal permission.**

**Similarity does not equal authorisation.**

---

## THE AH-S ENGINE

This repository is intended to evolve beyond a conventional website codebase.

It may contain reusable:

* UI components
* design-system primitives
* responsive systems
* animation systems
* conversion mechanisms
* SEO infrastructure
* analytics implementations
* accessibility systems
* interactive tools
* landing-page architecture
* internal development utilities
* deployment configuration
* experimental technology

Some systems may subsequently be extracted into internal AH-S frameworks or other proprietary products.

Do not assume that any component is available for independent reuse.

---

## ARCHITECTURE

The repository is structured to separate the public website from reusable infrastructure.

```text
ah-s/
│
├── website/
│   ├── app/
│   ├── components/
│   ├── lib/
│   ├── public/
│   ├── styles/
│   └── ...
│
├── README.md
└── ...
```

The architecture will evolve.

**Do not introduce structural changes simply because they appear cleaner in isolation.**

Changes must support maintainability, performance, scalability and the long-term AH-S technology strategy.

---

## PRODUCTION

This repository may be connected directly to production deployment infrastructure.

That means:

> **A careless commit can become a production incident.**

Before merging or deploying:

1. Test locally.
2. Test responsive behaviour.
3. Test interactive functionality.
4. Check console errors.
5. Check accessibility.
6. Check SEO.
7. Check performance.
8. Verify production configuration.
9. Review the diff.
10. Then deploy.

**Do not push untested code to production.**

---

## AI DEVELOPMENT

AI-assisted development may be used within this repository.

AI-generated code is **not automatically trusted**.

Every change remains subject to human review and must meet the project's requirements for:

* security
* accessibility
* performance
* maintainability
* correctness
* responsiveness
* SEO
* legal compliance

**"GPT generated it" is not an excuse for broken software.**

---

## DEPENDENCIES

Third-party packages must have a legitimate reason to exist.

Do not introduce dependencies merely because they make a small implementation easier.

Before adding a package, consider:

* bundle size
* security
* maintenance status
* licence
* performance
* native browser capabilities
* whether the functionality belongs in the AH-S codebase

**Dependency bloat is technical debt with an invoice attached.**

---

## DEVELOPMENT PRINCIPLES

### Build for the user.

Not for the developer.

### Keep it fast.

Every unnecessary script, dependency and request has a cost.

### Keep it accessible.

Accessibility is part of the product, not a final checklist.

### Keep it maintainable.

Clever code that nobody can maintain is not clever.

### Keep it intentional.

Every component should earn its existence.

### Keep it scalable.

Today's shortcut can become tomorrow's bottleneck.

### Protect the asset.

The AH-S codebase is a business asset.

Treat it accordingly.

---

## ⛔ DO NOT

Do not:

* commit secrets
* commit API keys
* commit passwords
* expose private credentials
* hard-code sensitive production configuration
* disable security controls to "make something work"
* install unnecessary dependencies
* duplicate components unnecessarily
* overwrite production configuration without understanding it
* remove existing functionality without checking dependencies
* deploy untested changes
* copy proprietary code into external projects

If you find a security issue:

**Do not publish it publicly.**

Report it directly to the appropriate AH-S administrator.

---

## LICENSING

Unless explicitly stated otherwise, the contents of this repository are **proprietary and all rights are reserved** by:

**ASTON H-S Ltd.**

No permission is granted to copy, modify, distribute, sublicense or commercially exploit the proprietary contents of this repository.

Third-party software remains governed by its respective licence terms.

---

## ENFORCEMENT

Unauthorised use of proprietary materials may constitute infringement of intellectual property rights and may result in appropriate action being taken.

This README is intentionally explicit.

**Do not interpret the absence of a warning on a particular file, component or asset as permission to use it.**

If you need permission:

**Ask.**

If you do not have permission:

**Do not use it.**

---

## AH-S™

**ASTON H-S Ltd.**

Proprietary technology.

Private repository.

Production system.

**Handle accordingly.**
