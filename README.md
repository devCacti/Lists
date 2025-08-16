# Lists

This repository serves as a website for storing lists in the local storage of the browser, it also features a shopping list mode similar to the one in the Cooking App. This one will only feature local storage, meaning you can't share information across devices.

## Storage Structuring (Like in DBs)

- List

  - ID
  - SectionName - _For Organization_
  - Name
  - Description
  - CheckListMode - _Enables Checkboxes for items_
  - IKnowThePrice - _Enables Price for items_
  - DateCreated
  - DateChanged

- List Item

  - ID
  - ListID - _Parent List ID_
  - Name
  - Description
  - Checked
  - Price
  - DateCreated
