
# data.gov.uk collection page checks
                    
This test uses Playwright to check the [collection content files](https://github.com/alphagov/datagovuk_find/tree/main/app/content/collections) from the datagovuk_find repository.

It fetches those files, extracts the list of urls (webistes, api, dataset) referred to the markdown frontmatter.

The tests visit the rendered html version of each collection page on data.gov.uk and ensures that:

- the links listed in the frontmatter are rendered on the page
- that those links are reachable
                    
                    
## Report

Using test results file: [results/collection-check-2026-11-05T1430.csv](results/collection-check-2026-11-05T1430.csv)



## Education statistics
Page: [https://data.gov.uk/collections/early-years/education-statistics](https://data.gov.uk/collections/early-years/education-statistics)


            

The following links were not reachable during test

- [https://explore-education-statistics.service.gov.uk/find-statistics?themeId=e6e31160-fe79-4556-f3a9-08d86094b9e8&sortBy=newest](https://explore-education-statistics.service.gov.uk/find-statistics?themeId=e6e31160-fe79-4556-f3a9-08d86094b9e8&sortBy=newest)



