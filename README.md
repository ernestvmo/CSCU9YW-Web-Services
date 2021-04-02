# CSCU9YW-Web-Services
This project was realized as a group assignment for the course CSCU9YW - Web Services at the University of Stirling.

## Assignment Problem
The aim of this assignment is to create a web service that acts as a contacts database. You may
use any web service technology you like: SOAP, REST based on javax (lab4), REST based on
Jakarta EE, and REST based on Spring io. For REST services you may use URI parameters,
XML or JSON for transferring data to/from the service. For SOAP you may use RPC or
Document literal encoding.
For SOAP and REST based on javax service and client should be provided. For Jakarta and
Spring the service is expected together with a record of requests to exercise the service. Credit
will be given for a basic web interface to interact with the service. In any case, a basic UI for the
client is sufficient, the focus for this assignment is on the web service element.


### The Contacts Service
The contact database service should store details of people in a java data structure such as a
HashMap (or external database if you prefer). Each person’s detail should include name,
firstname, address (street, town/city, postcode), and telephone number. You can assume that the
telephone number is unique and thus can be used to identify a contact.
The webservice should provide methods to retrieve, add, edit, and delete contacts. Advanced
features may include interacting with a group of contacts (e.g. all contacts in a specific town,
counts of edits of contacts etc). You may also try and may your web service more robust handling
potential error cases (adding an already existing contact, deleting one which does not exist).
Some credit will be available for such features.
