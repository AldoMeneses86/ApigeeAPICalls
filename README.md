# Application integration - Apigee API Calls

## Objective:
It is necessary to know the total number of API calls that are being generated in each of the environments created within Apigee.

## Introduction
Although after deploying Apigee it is necessary to constantly know the total number of API calls that are being generated in each of the environments, regardless of the subscription model we have (PAYG, Standard, Enterprise or Enterprise Plus) it is very important to know this information in order to manage our “bag” of acquired API calls and not find ourselves facing any surprises later.

This information can be retrieved from the Apigee reference, which is documented in the “next steps” section, as detailed the process involves the internal query of the Apigee API manually to obtain the API calls in a date range defined in said query, all this can be somewhat tedious or even forgotten due to the day-to-day workload, that is why with Application Integration an automatic process can be generated to obtain said information.
 
 
