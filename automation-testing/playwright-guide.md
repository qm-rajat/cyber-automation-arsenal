```markdown
# Playwright Guide

## Why Playwright?
- Fast execution
- Multi-browser
- Auto wait built-in

## Sample Example

```javascript
const { test, expect } = require('@playwright/test');

test('homepage has title', async ({ page }) => {
  await page.goto('https://example.com');
  await expect(page).toHaveTitle(/Example/);
});