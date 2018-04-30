# Sutton Coldfield Town Council

This repo contains data relating to Sutton Coldfield Town Council, used in the story [This is what Sutton Coldfield Town Council has spent money on since 2016](http://birminghameastside.com/2018/04/28/this-is-what-sutton-coldfield-town-council-has-spent-money-on-since-2016/). That includes:

* Expenditure above £250 (converted from PDFs on the SCTC website, cleaned, and combined)
* Statements of accounts
* Community grant data - documents and minutes
* Contract data

We primarily used information published on the town council's [Budget/Finance page](https://www.suttoncoldfieldtowncouncil.gov.uk/how-we-spend-your-money/budgetfinance/) - however, some information was sourced from meeting minutes and documents, while the most recent statement of accounts (not made available on the council's budget page) was found through advanced Google searches.

## How we did it

Below is a breakdown of each section of the article and how the data was sourced.

### Most of the money in the first year went unspent…

To get figures for how much of the budget was spent, how much was allocated for reserves, and how much was budgeted for specific purposes but remained unspent, we looked at the **annual accounts**. 

The [Statement of Accounts 2016-17](https://www.suttoncoldfieldtowncouncil.gov.uk/wp-content/uploads/2017/11/Statement-of-Accounts-2016-17.pdf) provides overall figures for money budgeted and spent in that year. The [Statement of Accounts 2017-18](https://www.suttoncoldfieldtowncouncil.gov.uk/wp-content/uploads/2018/04/Sutton-Coldfield-2018-Accounts-1.pdf) - not yet published on the Budget/Finance page - covers the last year.

The [internal audit report](https://www.suttoncoldfieldtowncouncil.gov.uk/wp-content/uploads/2017/11/Internal-Audit-Final-Report-2016-17.pdf) provided further context, such as that the council had not invested any of its reserved of over £1m.

Background on [the difference between earmarked reserves and general reserves can be found in documents like this](https://moderngovwebpublic.bromsgrove.gov.uk/documents/s4644/Reserves%20Policy-%20Appendix%20A.pdf)


### Only 2% of the Play and Recreation budget was spent in 2016/17

To get a further breakdown of specific budgets (e.g. play and recreation) versus spending we used the same documents.


### What does Sutton Coldfield spend its money on?/Consultants, a council, and a concert — who gets the most money

Further detail on spending was obtained from the **payments over £250** [published on the council finance page](https://www.suttoncoldfieldtowncouncil.gov.uk/how-we-spend-your-money/budgetfinance/). These only go as far as December 2017.

They are published in PDF format, so we converted them into spreadsheets using Wondershare. 

These spreadsheets were then combined using Open Refine, and cleaned using the same tool - for example in some cases slightly different spellings were used for the same recipient.

Further cleaning was done in Excel, including additional categorisation which allowed us to reach totals for broad categories such as 'overheads' (office costs, stationery, and so on)

Context for some contracts was taken from the [contracts 2016-17 breakdown](https://www.suttoncoldfieldtowncouncil.gov.uk/wp-content/uploads/2017/11/Contracts-2016-17.pdf), which identifies the supplier and period covered. 

Agenda items for council meetings could also provide extra detail, [such as this one on the Summer in Sutton CBSO concert](https://onedrive.live.com/?authkey=%21ANRqQMQCoQaKwoc&cid=663CAED515AB37FE&id=663CAED515AB37FE%2161765&parId=663CAED515AB37FE%2161764&o=OneUp) where it was proposed to spend the entire budget on one event.

### Community grants — not all wards are awarding the same funding

Community Grant data was the hardest to pin down. Overall spending is in the budget, but to get a breakdown by ward we needed to use a number of sources:

* Grant applications are [listed in PDF documents for each meeting](https://suttoncoldfieldlocal.co.uk/wp-content/uploads/2016/11/Copy-of-Community-Grant-Fund-Amenities-15-November..pdf) with the ward identified - these do not say whether the applications were approved, but expenditure data does say whether those organisations received money under the Community Grant category. Older meeting documents do not provide this detail, however.
* More recent committee meeting documents also include a breakdown of spending to date and budget by ward, such as [this one from January 17 2018](https://royalsuttonnews.uk/wp-content/uploads/2018/01/Summary-Table-Jan-2018.pdf). 
* The minutes for each meeting detail which applications were approved or rejected: [here are the minutes for the same January 17 2018 meeting](https://royalsuttonnews.uk/wp-content/uploads/2018/01/draft-minutes-v1-2.pdf). In some cases applications for the Community Grant fund are referred to other budgets. [Here are minutes from a meeting a year earlier](https://suttoncoldfieldlocal.co.uk/wp-content/uploads/2017/01/145-b-Minutes-17th-Jan-2017.pdf) and [one for March 2017](https://www.suttoncoldfieldtowncouncil.gov.uk/wp-content/uploads/2017/10/11077-Minutes_Draft_New.pdf)and [one for July 2017](https://www.suttoncoldfieldtowncouncil.gov.uk/wp-content/uploads/2017/10/15183-draft_minutes_vol_2.pdf). Sometimes there are additional documents for specific agenda items, [such as this on the Changing Places toilet proposal in January 2018](https://www.suttoncoldfieldtowncouncil.gov.uk/wp-content/uploads/2018/01/Changing-Places-Toilet-Facility-v1links.pdf)
* We used the [documents for March 13 2018 which show the last breakdown of the financial year](https://www.suttoncoldfieldtowncouncil.gov.uk/wp-content/uploads/2018/03/Summary-Table-March-2018.pdf) and then added grant awards made in the minutes [for the same meeting in March 2018](https://www.suttoncoldfieldtowncouncil.gov.uk/wp-content/uploads/2018/03/Item-153b-ALC-Min.pdf) when the final grant approvals of the financial year were made, to reach a total.
* [Community Grants Awarded in 2016/17](https://www.suttoncoldfieldtowncouncil.gov.uk/wp-content/uploads/2017/11/Community-Grants-Payments-2016-17.pdf) lists which ones were approved, but does *not* say which ward and budget they related to.
* The council website's [Community Grant Scheme page](https://www.suttoncoldfieldtowncouncil.gov.uk/apply-for-a-grant/community-grant-scheme/) lists the funding allocated for the last year, but again without ward details.
* Postcodes can be tied to wards by using [Doogal's postcode lookup service](https://www.doogal.co.uk/UKPostcodes.php): [this is the lookup for B72 1RN](https://www.doogal.co.uk/ShowMap.php?postcode=B72%201RN)

