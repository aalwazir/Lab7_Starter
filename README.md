# Lab 7
Ayat Alwazir

1. I would fit automated tests within a GitHub Action that runs whenever code is pushed. This is the best option because it automatically checks whether new changes break existing functionality before the code is merged or shared. It also makes testing consistent because every push is tested the same way, instead of relying on developers to remember to run tests manually. Manually running tests locally before pushing is less reliable because someone may forget to run them. Running tests only after all development is completed is the weakest option because bugs are found too late, making them harder to fix.
2. No, I would not use end-to-end testing to check if a function is returning the correct output because E2E tests are meant to test full user workflows through the webpage. I would use a unit test to check one function’s output.
3. Navigation mode analyzes the page right after it loads and gives an overall report about initial page load performance. Snapshot mode analyzes the page in its current state, so it is better for checking current accessibility issues, but it does not measure the full page-load process or JavaScript changes over time.
4. 
   - Use <html> element with a [lang] attribute so that accessibility improves.
   - Create a meta description for the document so that search engines can better understand the content will improve SEO.
   - Improve caching by increasing the cache lifetime for static assets. Longer caching could make repeat visits faster.