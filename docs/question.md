## Business Requirement

A water utilities company needs a report (PowerBI or Tableau) to share insights to their business to improve their strategic decision making.

The main insights they need are:

1. The state of the flow of water and waste per city
2. The chance of there being any blockages in the pipes in the near future
3. A visual view of the historical blockages

The available data sources are:

- Address data is stored in SAP as well as a legacy MongoDB database.
  - The only way to join these datasets at the moment is by comparing the postal code and the street names.
- Water and waste pressure and flow data stored in SCADA
  - Produces data every 15 minutes
  - Right now we do not have access to this data, but the SCADA development team has built a streaming solution and just needs us to tell them where it must be streamed.
- Predictive and past rainfall data from a public RESTful API
  - Updated once a day.

## Your Data Architecture Assignment

Draft a data solution architecture document, detailing the basic architectural components/design of the system, key considerations when designing the solution and some limiting factors that may be important in the design of the solution.

There are no “gotchas” in this assignment and perfection is not expected - the evaluation is based on how you approach the problem, not whether you have all the answers.

Additional Guidelines

- You have no constraints about which technologies to use, as long as it’s a cloud-based solution and takes cost efficiency into account.
- The team that will implement your solution with you and then extend it based on future feature requirements contains 3 data engineers, 1 data scientist and 1 data analyst.
- You do not need to explain the reporting or data science components of the solution.
- Focus on what you know rather than spending hours researching all the possible tools and tech stacks available - we’ve all been down that endless rabbit hole!
  - When you do think that there are perhaps better tools available, simply indicate that you will research and compare. No need to do this research now.
- Try to use the correct terminology/jargon - assume your document is intended for a technical audience.
