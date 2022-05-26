Project B Team 1 Sprint 3 Retrospective
- **Description of user stories and test cases we completed this sprint**
  - Completed user stories
    - Edit Post
      - As a donor, I want to be able to edit my item posts, so that recipients can have accurate information about my items
    - Delete Post
      - As a donator, I want to be able to delete a post, so recipients know this is item is no longer available
    - Browse Items
      - As a recipient, I want to be able to see what items have been posted, so that I can find what items I need
    - Donor Historic Record
      - As a donor, I want to have a historic record, so I can view what items I have donated in the past.
    - View More Information
      - As a recipient, I want to be able to view: the description, category, delivery method, condition, and quantity of item(s) in a donor's active post, so that I can evaluate whether or not my organization would be able to receive, or benefit from receiving, the posted donation.
    - Message Donor
      - As a recipient, I want to be able to message the donor, so that I can let them know I am interested in receiving an item they have posted
   - Started user stories
      - Filter
        - As a recipient, I want to be able to filter items, so that I can find items that fit my needs.
          - working for some filters
  - Completed test cases (espresso tests) 
    - Donor edit post item details
    - Donor edit post item image
    - Donor delete post
    - Recipient email donor
    - Recipient browse items
    - Recipient see more item info
    - Donor see more item info
    - Donor view historic record
    - Donor view more item info in historic record
    - Donor view empty historic record
    - Donor add to historic record
    - Donor delete from historic record
    - Donor try to edit from historic record
    - Donor try to add item to historic record that is already in historic record
  - Completed test cases (Junit tests)
    - test newItemInfo class constructor, getter, and setter methods with email and recipient name added to class
 - **Team Reflection**
   - Chloe completed the view more information, edit post, delete post, and message donor activities and 
  worked on creating tests for new activities created this sprint
   - Megan added four new activities to be able to "post" an item to a new branch in the database to mark items as donated to create the donor historic record and then view the items in the donor historic record
   - Matthew Scott made the item list view in the recipient layout and the filters for item listing (Matthew Stewart helped with filter too)
   - This sprint we were able to complete more than past sprints because we have a better understanding of the databases we have created on Firebase and are more familier with Android Studio and github
   - We learned that some of the original functionalities we had planned on creating for this app were much more complex than 
  originally thought so we had to rework some of the activities so we could finish as much as possible for the final sprint
   - Originally we thought that we could have notifications between recipients and donors and an in-app messaging system,we also wanted recipients to be able to favorite items and to be able to create a wishlist and receive notifications if an item from their list waas posted, we were also not able to complete the recipient historic record