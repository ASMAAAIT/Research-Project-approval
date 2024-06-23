Tasks
0. Share your MVP specification!
mandatory

Share a link here to a NEW Google Document where each of the following tasks are addressed.

Add URLs here:
Save

 Done? Help

1. Rename the document
mandatory

Rename the document to be the Project's name and append " MVP specification"

 Done? Help

2. Architecture
mandatory

In a section named "Architecture":

Include an illustration or diagram of the Portfolio Project's MVP. This should include an end-to-end map for the data flowing through your system. Each part of the diagram should be clearly labeled.
Here are some resources to learn more:

Web Architecture 101
List of tools to create architecture diagrams
Web Application Architecture
 Done? Help

3. APIs
mandatory

In a section called "APIs and Methods":

List and describe the API routes that you will be creating for your web client to communicate with your web server

Example:
/api/rewards
GET: Returns a randomized array of ten rewards based on rarity for a user to win based on a roll POST: Takes a user id and reward id and adds that to the user rewards table
/api/user
GET: Returns the user's information based on session id
/api/job_search
POST: Returns job's matching the parameters through GitHub Jobs API

List and describe any API endpoints or function/methods that you will be creating to allow any other clients to use:

Example:
class arrow.arrow.Arrow(year, month, day, hour=0, minute=0, second=0, microsecond=0, tzinfo=None)
An Arrow object.
Implements the datetime interface, behaving as an aware datetime while implementing additional functionality.

Parameters
year -- the calendar year.
month -- the calendar month.
day -- the calendar day.
hour -- (optional) the hour. Defaults to 0.
minute -- (optional) the minute, Defaults to 0.
second -- (optional) the second, Defaults to 0.
microsecond -- (optional) the microsecond. Defaults 0.
tzinfo -- (optional) A timezone expression. Defaults to UTC.
(source https://arrow.readthedocs.io/en/latest/#api-guide)

List and describe any 3rd party APIs that you will be using

e.g. https://developer.twitter.com/en/docs/tweets/post-and-engage/overview
POST statuses/update
POST statuses/destroy/:id
GET statuses/show/:id
GET statuses/oembed
GET statuses/lookup

If there are no APIs used or provided, skip this section.

 Done? Help

4. Data Modelling
mandatory

In a section named "Data Model":

Create a data model diagram to clarify how data will be stored
Tools: SqlDBM

Example: 


 Done? Help

5. User Stories
mandatory

First, research what user stories are, and how to write them. Also note some pitfalls of creating user stories that are too general.

In the "User Stories" section:

Define 3-5 detailed user stories that will be satisfied when your MVP is complete.
 Done? Help

6. Mockups
mandatory


