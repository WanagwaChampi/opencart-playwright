# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: LoginDataDriven.spec.ts >> Login Test with CSV Data: Invalid login @datadriven
- Location: tests\LoginDataDriven.spec.ts:55:8

# Error details

```
Error: locator.click: Target page, context or browser has been closed
Call log:
  - waiting for locator('span:has-text("My Account")')

```

```
Error: apiRequestContext._wrapApiCall: Target page, context or browser has been closed
```