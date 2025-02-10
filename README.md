# Next.js 15 Server Component Error Handling Bug

This repository demonstrates a potential bug in Next.js 15 server components involving silent failures during nested data fetching.  When an error occurs in a nested API call within a server component, the error may not be properly propagated, resulting in unexpected behavior on the client-side.

The `serverComponentBug.js` file shows the problematic code, while `serverComponentSolution.js` provides a solution implementing robust error handling.

## How to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Observe the unexpected behavior in the browser.
5. Compare with the solution in `serverComponentSolution.js`.