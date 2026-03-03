
# Project Name

...

## Project Description

...

## Motivation

...

## Key Takeaways
- [Item 1]
- [Item 2]

## Installation


```bash
pnpm create playwright
```

## Usage

```bash
pnpm exec playwright test                     # run all tests headless
pnpm exec playwright test --headed            # run with visible browser
pnpm exec playwright test --ui                # interactive UI mode
pnpm exec playwright test --trace on          # run with trace recording for debugging
pnpm exec playwright test --project=chromium  # run on Desktop Chrome only
pnpm exec playwright test --debug             # debug mode
pnpm exec playwright codegen                  # auto-generate tests by recording actions
```


## Learning (Days 1-2)

### Core Concepts
1. **Locators** — user-facing selectors (getByRole, getByText), not CSS selectors
2. **Web-First Assertions** — expect() auto-retries, no manual waits
3. **Actionability** — auto-waiting before click (visible, stable, enabled, not covered)
4. **Projects** — multi-viewport testing (desktop + mobile) from one config
5. **Trace Viewer** — step-by-step debugging with DOM snapshots and network

### Exercises
- Test against playwright.dev: click "Get started", assert "Installation" heading
- No CSS selectors, no waitForTimeout, no waitForSelector
- Add mobile project to config, run same test in both viewports
- Run with --trace on, inspect in Trace Viewer



## Code Structure

...

## Demo

**First run**

![first run](./figs/first-run.png)

## Points of Interest
- [Item 1]
- [Item 2]

## References
- [Link/Reference 1]
- [Link/Reference 2]
