# Uruguay Properties - Bug Reports

## BUG-001 - Missing Favicon

### General Information

- Date: 2026-11-25
- Build Version: 0.1
- Environment: Local Development
- Related Test Case: ST-007
- Severity: Low
- Priority: Low
- Status: Open

### Description

The browser fails to load the website favicon.

### Steps to Reproduce

1. Open the application in Chrome.
2. Open Developer Tools using F12.
3. Select the Console tab.
4. Reload the page.
5. Observe the console messages.

### Expected Result

The page loads without resource errors.

### Actual Result

The browser displays a 404 Not Found error
for the favicon.ico resource.

### Impact

The main application remains functional.
A missing resource error appears in the console.
### Resolution

Created a valid SVG favicon and linked it
correctly in the HTML document.

### Retesting

- Favicon displays correctly.
- No resource loading errors.
- Navigation remains functional.

### Final Result

Pass.