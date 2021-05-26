JsonPowerDB is a Database Server with Developer friendly REST API services. It's a High Performance, Light Weight, Ajax Enabled, Serverless, Simple to Use, Real-time Database.

Easy and fast to develop database applications without using any server side programming / scripting or without installing any kind of database.

Whether it's a Dynamic Website or a Mobile App or some Data Analytics Portal, the development is real fun and fast

**Use Cases**

**All Dynamic web applications.**

All Mobile applications that require backend database.

Session Caching.

Page Caching.

Existing Database applications to improve their reporting / analytics performance.

Best suited as backend Database for IoT.

Live HTML templates / themes.

Any software application that needs backend database.

**Products**

To suit every application’s backend database requirements.

Shared JPDB - free / low cost DBSaaS: 

Downloadable and freemium JPDB instance:

Dedicated JPDB instances:

Customized JPDB as per requirement

**Features**

JsonPowerDB (JPDB) is Next Generation, Creative and Disruptive Multi-mode DBMS_ with many USPs.

Proprietary algorithm for High Performance CRUD operations. Multiple times faster than popular DBMS.

Serverless support for faster development - A UI developer can develop complete dynamic application.

DBMS with built in web / application server and embedded caching makes the performance lightning fast.

Server side Native NoSQL - best query performance.

In-built support to query on multiple JPDB databases.

Multi-mode DBMS - Document DB, Key-Value DB, RDBMS support.

Schema free - easy to develop and maintain.

Web-services API - Can be used with any programming language that has support for HTTP.

Enriched by a pluggable API Framework - A developer can develop a pluggable API and plugin into any of our cloud JPDB instance.

Standardisation of API development framework makes the development process easy, more readable, and less error prone.

Multiple security layers.

Nimble, Simple to use, In Memory, Real-time DBMS.

**JPDB API Command Reference

Language Syntax**
< . . . > - User specified value.
<< . . . >> - Optional parameter, may take default value if not used.

# Connection Token - Connecting to JPDB API.

Connection-token is used to interact with JsonPowerDB, it must be included in every request of jsonPowerDB for security purpose.
# How to get the 'connection-token' from JsonPowerDB :

Login to JPDB API Dashboard .

Click on Tools option on left navigation .

Select Tokens panel and then select 'connection-token' option from dropdown ,

Copy the 'connection-token' from the Token table.

And if there is no 'connection-token' in the token table or if you want to generate a new 'connection-token', click on the Generate Connection_Token button as It will generate a new-connection token.

Copy the newly generated 'connection-token' from token table.
# Response Headers in JPDB :

One or more of the following information may be returned in the response, all of which give time in milliseconds unit. All information will be returned with IML, IRL, IDL, ISL APIs.

serverTime - Time between receiving request and returning response by JsonPowerDB Server.

reqResTime - Time taken to convert request to reponse by the API (not in the KVP API). It's the combination of parseTime and execTime.

parseTime -Time taken to parse and validate the request.

execTime - Actual time of executing the validated request.


