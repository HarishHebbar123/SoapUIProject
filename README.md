# SoapUI Project

## Description

Task1: API

* Perform API request to produce a list of dog breeds: Refer -> `All Request`
* Using Code verify "retriever" breed is with in the list : Refer -> 'All Request' and 'Breeds' (Assertion and Xpath) used. Xpath Code is		   "boolean(//*:message/*:${#TestCase#breed})"
* Perform an API request to produce a list of sub-breeds for retriever: Refer -> 'list Request'
* Perform an API request to produce a random image/link for the sub-breed 'golden': Refer -> 'random Request'

Steps:

* Added Resource to "All Request" i.e /api/breeds/list/all
* Parameterized the Resource value of "list Request" i.e /api/breed/{breed}/list
* Added Parameter value and Style to "retriever" breed request
* Parameterized the Resource value of "random Request" i.e /api/breed/{breed}/{subbreed}/images/random
* Added breed, subbreed_count and subbreed variables to Test Case properties
* Added Test Suite,Test Case and Test Steps to execute the API calls.

## Requirements

* SOAP UI 5.5.0

## Run Instructions

1. Double click on the TestCase1 and click on the Run.
2. When Test Finish, all the above API calls will be executed and results will be displayed with steps.
