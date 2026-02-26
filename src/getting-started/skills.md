# 🧠 Bagisto Agent Skills

Enhance your Bagisto development workflow with AI-powered agent skills designed specifically for Bagisto projects.

These skills provide domain-specific, reusable intelligence for AI agents such as Claude Code, Cursor, Windsurf, and other AI-powered development tools.

## What is `bagisto/agent-skills`?

`bagisto/agent-skills` is a collection of specialized AI skills that improve how AI tools understand and work within a Bagisto codebase.

::: info Why Use Agent Skills?
These skills give AI agents deeper awareness of Bagisto’s architecture, testing workflows, and payment integrations — resulting in more accurate code generation and smarter development assistance.
:::

## Benefits for Developers

Agent skills help with:

- 🧪 **Structured Testing Workflows** – Generate Pest tests with proper assertions and architecture patterns
- 💳 **Payment Gateway Integrations** – Implement Stripe, PayPal, and custom gateways correctly
- 🏗️ **Bagisto Architecture Awareness** – Follow package and module conventions
- 🎯 **Smarter Code Suggestions** – Context-aware development guidance
- 🚀 **Faster Development** – Reduce repetitive implementation work

## Available Skills

We currently provide two specialized AI skills:

## 📦 Package Development

**Skill**: `package-development`
**Purpose**: Package development in Bagisto.

**Activates when:**

- Creating packages
- Writing migrations
- Creating models and repositories
- Defining routes and controllers
- Building views and localization
- Implementing DataGrid
- Creating menus and ACL
- Adding system configuration

Or when the user mentions:

- `package`
- `migration`
- `model`
- `repository`
- `controller`
- `DataGrid`
- `menu`
- `ACL`

## 🚚 Shipping Method Development

**Skill**: `shipping-method-development`
**Purpose**: Shipping method development in Bagisto.

**Activates when:**

- Creating shipping methods
- Integrating shipping carriers like FedEx, UPS, DHL
- Adding delivery logic
- Adding new shipping options to checkout

Or when the user mentions:

- `shipping`
- `shipping method`
- `shipping carrier`
- `delivery`
- Adding a new shipping option

## 💳 Payment Method Development

**Skill**: `payment-method-development`
**Purpose**: Payment gateway development in Bagisto.

**Activates when:**

- Creating payment methods
- Integrating Stripe, PayPal, or third-party processors
- Adding new checkout payment options

Or when the user mentions:

- `payment`
- `payment gateway`
- `payment method`
- `Stripe`
- `PayPal`
- Adding a new checkout payment option

## 🛍️ Product Type Development

**Skill**: `product-type-development`
**Purpose**: Product type development in Bagisto.

**Activates when:**

- Creating custom product types
- Defining product behaviors
- Implementing specialized product logic

Or when the user mentions:

- `product type`
- `custom product`
- Implementing product-specific behavior

## 🧪 Pest Testing

**Skill**: `pest-testing`
**Purpose**: Tests applications using the Pest 3 PHP framework.

**Activates when:**

- Writing unit or feature tests
- Adding assertions
- Testing Livewire components
- Performing architecture testing
- Debugging failing tests
- Working with datasets or mocking
- User mentions:
  - `test`
  - `spec`
  - `TDD`
  - `expects`
  - `assertion`
  - `coverage`
  - Verifying functionality works

## Setup Instructions

### Install All Skills

Install all available skills into your AI agent:

::: code-group

```bash [Install All Skills]
npx skills add bagisto/agent-skills
```

:::

### Install a Specific Skill

::: code-group

```bash [Pest Testing]
npx skills add bagisto/agent-skills --skill "pest-testing"
```

```bash [Payment Method Development]
npx skills add bagisto/agent-skills --skill "payment-method-development"
```

:::

### Install for a Specific AI Agent

::: code-group

```bash [Claude Code]
npx skills add bagisto/agent-skills -a claude-code
```

```bash [Cursor]
npx skills add bagisto/agent-skills -a cursor
```

:::

## Repository Structure

```
agent-skills/
├── skills/
│   ├── pest-testing/
│   ├── payment-method-development/
│   ├── shipping-method-development/
│   ├── package-development/
│   ├── product-type-development/
│   └── ...
├── AGENTS.md
└── README.md
```

## Supported AI Tools

These skills are compatible with:

- Claude Code
- Cursor IDE
- Windsurf
- Any AI agent supporting the `skills` CLI

::: tip Getting Started
For full AI assistance in Bagisto projects, install all skills. If you work in a specific area (like testing or payments), install only the relevant skill.
:::

## Best Practices

### Skill Management

- Install only the skills relevant to your workflow
- Keep skills updated alongside Bagisto upgrades
- Use clear prompts to trigger the correct skill activation

::: warning Important
Ensure the skills are installed in the correct environment where your AI agent operates, otherwise activation may not work properly.
:::
