!!! note ""
    While I think **simplifying taxes for startups** is an attractive opportunity generally, getting to product-market fit will depend on selecting the right initial problem to tackle, building the right solution, and using the right business model.  Since I don't know what those are yet, I'll just list all the ideas I have.

## Product ideas

### Tax checker for tech startups

* Check status of compliance with federal, Delaware, and California tax laws
    * Did you register as a California foreign corp?
    * Did you file the California statement of information? ([penalty](https://www.ftb.ca.gov/businesses/SOS-Penalty.shtml))
* Analyze past tax filings for tax savings such as:
    * Not getting R&D payroll credits ([explanation](https://www.mossadams.com/articles/2016/february/r-d-credit-can-help-offset-payroll-taxes))
    * Not withholding tax for international contractors/employees ([explanation](https://www.quora.com/What-does-a-US-based-company-need-to-do-to-comply-with-IRS-regulations-in-paying-foreign-contractors/answer/Wray-Rives?srid=1QR))
    * Not expensing business travel/meals
* Monetize by amending returns for a fee equal to a percentage of the savings found

### Tax checker for tech workers

* Analyze past tax filings for tax savings such as:
    * Paying double tax on RSU/option exercise because of wrong basis ([how this can happen](https://news.ycombinator.com/item?id=14113412#up_14118328))
    * 2 working parents not using the childcare credit
    * Charitable donations, found by searching for matching email receipts via Gmail API
    * Deductible health care expenses
* Monetize by amending returns for a fee equal to a percentage of the savings found

### API for sales tax and VAT

* Build an API that provides the applicable sales tax and VAT for a given location
* Build integrations starting with Salesforce, Stripe, etc.

## Business models

### SaaS with PS <small>(Avalara, Zuora)</small>

* Subscription revenues with different bundles depending on level of service  
* Include professional services for complex tax situations and custom integrations
* Scale by serving larger customers

### Pure SaaS <small>(Gusto, Stripe)</small>

* Subscription revenues that scale with number of transactions or employees
* Don't offer professional services
* Scale by serving small businesses in more verticals

### Affiliate revenues <small>(Mint, Credit Karma)</small>

Offer free apps to collect data.  Refer qualified leads to:

* Accountants: complex tax situtations, international
* Banks, online lenders and VCs: companies with track record of revenue growth