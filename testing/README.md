
# data.gov.uk collection page checks
                    
This test uses Playwright to check the [collection content files](https://github.com/alphagov/datagovuk_find/tree/main/app/content/collections) from the datagovuk_find repository.

It fetches those files, extracts the list of urls (webistes, api, dataset) referred to the markdown frontmatter.

The tests visit the rendered html version of each collection page on data.gov.uk and ensures that:

- the links listed in the frontmatter are rendered on the page
- that those links are reachable
                    
                    
## Report

Using test results file: [results/collection-check-2026-09-25T1140.csv](results/collection-check-2026-09-25T1140.csv)



## Child height and weight
Page: [https://data.gov.uk/collections/early-years/child-height-and-weight](https://data.gov.uk/collections/early-years/child-height-and-weight)


            

The following links were not reachable during test

- [https://publichealthscotland.scot/publications/show-all-releases?id=20566](https://publichealthscotland.scot/publications/show-all-releases?id=20566)

- [https://www.opendata.nhs.scot/dataset/primary-1-body-mass-index-bmi-statistics](https://www.opendata.nhs.scot/dataset/primary-1-body-mass-index-bmi-statistics)



## Childhood vaccinations
Page: [https://data.gov.uk/collections/early-years/childhood-vaccinations](https://data.gov.uk/collections/early-years/childhood-vaccinations)


            

The following links were not reachable during test

- [https://www.opendata.nhs.scot/dataset/childhood-immunisation-statistics](https://www.opendata.nhs.scot/dataset/childhood-immunisation-statistics)

- [https://scotland.shinyapps.io/phs-vaccination-surveillance/](https://scotland.shinyapps.io/phs-vaccination-surveillance/)

- [https://phw.nhs.wales/knowledge-article/cover-national-childhood-immunisation-uptake-data/](https://phw.nhs.wales/knowledge-article/cover-national-childhood-immunisation-uptake-data/)

- [https://www.publichealth.hscni.net/publications/annual-immunisation-and-vaccine-preventable-diseases-reports](https://www.publichealth.hscni.net/publications/annual-immunisation-and-vaccine-preventable-diseases-reports)



## Early years development review
Page: [https://data.gov.uk/collections/early-years/early-years-development-review](https://data.gov.uk/collections/early-years/early-years-development-review)


            

The following links were not reachable during test

- [https://www.opendata.nhs.scot/group/early-child-development](https://www.opendata.nhs.scot/group/early-child-development)



## Aerial photography
Page: [https://data.gov.uk/collections/environment/aerial-photography](https://data.gov.uk/collections/environment/aerial-photography)


            

The following links were not reachable during test

- [https://environment.data.gov.uk/dataset/dae203a8-ba24-4c54-bab0-866b9faadb58](https://environment.data.gov.uk/dataset/dae203a8-ba24-4c54-bab0-866b9faadb58)



## Flood alerts
Page: [https://data.gov.uk/collections/environment/flood-alerts](https://data.gov.uk/collections/environment/flood-alerts)


Check the following links are on the page above - the test does report false positives:

- https://environment.data.gov.uk/dataset/88bed270-d465-11e4-8669-f0def148f590


            


## Pupil attendance
Page: [https://data.gov.uk/collections/people/pupil-attendance](https://data.gov.uk/collections/people/pupil-attendance)


            

The following links were not reachable during test

- [https://explore-education-statistics.service.gov.uk](https://explore-education-statistics.service.gov.uk)



