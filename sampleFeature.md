# *feature title*

As a  
I would like  
So that

JIRA REF: jira url
Designs: link to design repository

### DATA

|Service                        | API                     |
|-------------------------------|-------------------------|
|e.g name of CMS                | e.g service request     |
|e.g name of dependant service  | e.g service request     |


### Generic Acceptance Criteria

+ IT Should return:
  + Product ID
  + Product Type
  + Product Name
  + Product Description
  + Product Image
  + Product availability

+ IT should display products of type A first
+ IT should only show products which are available
+ IT should not display any products where one or more fields are empty

### Device Specific Acceptance criteria

+ IT Should not display images on devices with a viewport <320px

### Error Handling Acceptance Criteria

+ IT Should display "No products currently available" where no products can be returned
+ IT Should provide a link to the parent page 

### Reporting Acceptance Crteria

+ IT Should apply tags to capture click events on:
  + Image
  + Description

 
