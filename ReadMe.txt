
1. Step: 
In appropriate folder (correct path) in terminal, add next data: 
npm init playwright@latest, then select: 
Initializing project in '.'
√ Do you want to use TypeScript or JavaScript? · TypeScript
√ Where to put your end-to-end tests? · tests
√ Add a GitHub Actions workflow? (y/N) · false
? Install Playwright browsers (can be done manually via 'npx playwright install')? (Y/n) » true
2. Commands for running TCs and their results in HTML:
npx playwright test
--after execution--
npx playwright show-report
--run test for the specific browser--
npx playwright test --project=chromium
--showing execution in bowser--
npx playwright test --project=chromium --headed
-- run certain file: example.spec.ts --
npx playwright test example.spec.ts--project=chromium
-- run certain test in selected file for testing--
npx playwright test -g "has title" --project=chromium
only and skip for executing selected TC.