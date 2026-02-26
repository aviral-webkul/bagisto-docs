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

```bash [Shipping Method Development]
npx skills add bagisto/agent-skills --skill "shipping-method-development"
```

```bash [Package Development]
npx skills add bagisto/agent-skills --skill "package-development"
```

```bash [Product Type Development]
npx skills add bagisto/agent-skills --skill "product-type-development"
```

:::

## Available Skills

We currently provide following specialized AI skills:

### 📦 Package Development

**Skill**: `package-development`

**Purpose**: Package development in Bagisto.

Run the following command to install the specified skill:

```
npx skills add bagisto/agent-skills --skill "package-development"
```

### 🚚 Shipping Method Development

**Skill**: `shipping-method-development`

**Purpose**: Shipping method development in Bagisto.

Run the following command to install the specified skill:

```
npx skills add bagisto/agent-skills --skill "shipping-method-development"
```

### 💳 Payment Method Development

**Skill**: `payment-method-development`

**Purpose**: Payment gateway development in Bagisto.

Run the following command to install the specified skill:

```
npx skills add bagisto/agent-skills --skill "payment-method-development"
```

### 🛍️ Product Type Development

**Skill**: `product-type-development`

**Purpose**: Product type development in Bagisto.

Run the following command to install the specified skill:

```
npx skills add bagisto/agent-skills --skill "product-type-development"
```

### 🧪 Pest Testing

**Skill**: `pest-testing`

**Purpose**: Tests applications using the Pest 3 PHP framework.

Run the following command to install the specified skill:

```
npx skills add bagisto/agent-skills --skill "pest-testing"
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
