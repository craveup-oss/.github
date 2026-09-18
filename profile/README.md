# Crave Open Source

Open-source tools, frameworks, and protocols for building better digital
hospitality.

CraveJS is our contribution to the community: reusable storefront foundations,
SDKs, order-management building blocks, and developer tooling for restaurant and
hospitality teams. We also maintain independent open protocols where a
vendor-neutral contract serves the ecosystem better.

Start with a credential-free demo, adapt a template, or contribute to an open
protocol.

[Run a loyalty walkthrough](https://opensource-loyalty.vercel.app/#walkthrough)
· [Explore the projects](https://github.com/orgs/craveup-oss/repositories)
· [Read the developer docs](https://docs.craveup.com)

## Choose your starting point

| I want to… | Start here |
| --- | --- |
| Build a web storefront | [CraveJS Web Template](https://github.com/craveup-oss/cravejs-web-template) — a fixture-backed Next.js restaurant storefront with six visual directions |
| Build for iOS and Android | [CraveJS Expo Template](https://github.com/craveup-oss/cravejs-expo-template) — a React Native storefront foundation with generated brand configuration |
| Add or integrate loyalty | [Loyalty Interchange Protocol](https://github.com/craveup-oss/loyalty-interchange-protocol) — an Apache-2.0 protocol, reference runtime, SDK, Admin, and conformance suite |
| Build a Flutter storefront | [CraveJS Storefront SDK for Dart](https://github.com/craveup-oss/cravejs-storefront-sdk-dart) — a typed preview client for the Storefront API |
| Connect an AI agent to Crave | [Crave Up MCP Server](https://github.com/craveup-oss/craveup-mcp) — local tooling for onboarding, menus, locations, readiness, and guarded releases |

## Try something without an account

Run checkout through refund in the
[LIP browser walkthrough](https://opensource-loyalty.vercel.app/#walkthrough),
or run the web storefront locally with fixtures and no Crave credentials:

```bash
git clone https://github.com/craveup-oss/cravejs-web-template.git
cd cravejs-web-template
corepack enable
pnpm install --frozen-lockfile
pnpm dev:fixtures --profile standalone-cli --tenant fixture-base
```

## Legacy storefront references

These MIT-licensed repositories preserve visual and interaction ideas from the
retired Storefront SDK 1.x. They are useful as design references, but they are
not production starters. Start new storefronts with the
[CraveJS Web Template](https://github.com/craveup-oss/cravejs-web-template).

- [Bakery storefront](https://github.com/craveup-oss/restaurant-storefront-starter)
- [Noodle-house storefront](https://github.com/craveup-oss/chinese-restaurant-storefront)
- [Sushi storefront](https://github.com/craveup-oss/sushi-restaurant-storefront)

## How we build

Our public projects favor explicit contracts, reproducible releases, secure
defaults, merchant-controlled data access, and demos that clearly distinguish
fixtures from connected environments.

Review each project's README for its current maturity and setup requirements.
Open an issue or follow its contribution guide to get involved.

[Browse all projects →](https://github.com/orgs/craveup-oss/repositories)
