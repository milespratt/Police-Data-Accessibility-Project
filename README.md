# Police Data Accessibility Project

# Join the Slack: https://join.slack.com/t/policeaccessibility/shared_invite/zt-eji7fh9w-slynNpPJtcGLUUhbhBmbTg

# Rough Mission Statement (will evolve):

It is my belief that perhaps the single most effective way we can make concrete progress toward this goal is in the realm of data accessibility. Specifically the accessibility of granular, local, county level police citation data.

This however, is a big undertaking, as most counties have clumsy/antiquated systems for searching for and extracting this type of data, and almost none have fully exposed datasets.

Ultimately, the future goal for this initiative is to:

Request (via FOIA) or Scrape, and then clean and aggregate county level police citation data for as many counties as possible, and to most importantly make this data open and free to the public.
I believe doing so will enable citizen data scientists and data journalists to then make progress on analysis, whereby they will serve the public by looking for and finding trends and anomalies in police behavior, leading to more accountability for both individual police officers and their larger police organizations.




# Initial Goals:

Scraping:

1. Many counties outsource their court records data to third party vendors such as Tyler Technologies. Finding and building scrapers for portals that are the same for many counties seems like a great early goal. A list of counties court record systems and their vendors must be made. This will be done collaboratively in [this Google Sheet](https://docs.google.com/spreadsheets/d/1nD4LnjU1b1b9RgQNcn6op-Oj3ZQVcgz-2bUgEU5RVXA/edit). For more details see https://github.com/Police-Data-Accessibility-Project/Police-Data-Accessibility-Project/issues/6.

2. Finding and writing scrapers for other large counties. Prioritize counties with easier to scrape systems first. 

For guidelines to contributing to scraping, please see https://github.com/Police-Data-Accessibility-Project/Police-Data-Accessibility-Project/blob/master/CONTRIBUTING.md

# Freedom of Information Act Requests:

3. Researching a data request template with all the data we want to ask for in FOIA requests

4. Submitting FOIA requests and monitoring responses


I will be adding tasks to the projects section of this repo, so we can all keep track of them there.


If you are looking to start building a scraper, the csv file above has the URLS of all most US counties' public records portals. 

# The fields we would like to make sure to collect at a minimum from any scrape are:

**For anything labeled PII: do not scrape personally identifiable information yet. We are consulting with lawyers on implications for this, but intend to do so once given the green light. 

* _id
* _state
* _county
* CaseNum
* FirstName (PII)
* MiddleName (PII)
* LastName (PII)
* Suffix
* DOB
* Race
* Sex
* ArrestDate
* FilingDate
* OffenseDate
* DivisionName
* CaseStatus
* DefenseAttorney (PII)
* PublicDefender (PII)
* Judge (PII)
* ChargeCount
* ChargeStatute
* ChargeDescription
* ChargeDisposition
* ChargeDispositionDate
* ChargeOffenseDate
* ChargeCitationNum
* ChargePlea
* ChargePleaDate
* ArrestingOfficer (PII)
* ArrestingOfficerBadgeNumber.  (PII)

