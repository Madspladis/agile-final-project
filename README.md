---
name: User Story
about: Standard user story template
title: ''
labels: ''
assignees: ''
---

## User Story

As a shopper,  
I need to create a product in the catalog,  
So that I can add new items for sale.

## Acceptance Criteria

Given I have valid product data,
When I send a POST request to /product,
Then the product is created and returned with a unique ID.
