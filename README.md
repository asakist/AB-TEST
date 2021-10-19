AB Testing
-----------

-Task statement:
--------------
  You've received an analytical task from an international online store. 
  Your predecessor failed to complete it: they launched an A/B test and then quit (to start a watermelon farm in Brazil). 
  They left only the technical specifications and the test results.

-Technical description:
------------
  Test name: recommender_system_test
  Groups: А (control), B (new payment funnel)
  Launch date: 2020-12-07
  The date when they stopped taking up new users: 2020-12-21
  End date: 2021-01-01
  Audience: 15% of the new users from the EU region
  Purpose of the test: 
  Testing changes related to the introduction of an improved recommendation system
  Expected result: 
  within 14 days of signing up, users will show better conversion into product page views (the product_page event), 
  product card views (product_card) and purchases (purchase). At each of the stage of the funnel product_page → product_card → purchase, there will be at least a 10% increase.
  
- Data description:
------------
  ab_project_marketing_events_us.csv — the calendar of marketing events for 2020
  final_ab_new_users_upd_us.csv — all users who signed up in the online store from December 7 to 21, 2020
  final_ab_events_upd_us.csv — all events of the new users within the period from December 7, 2020 to January 1, 2021
  final_ab_participants_upd_us.csv — table containing test participants
  
#Goal:
---------
  Complete the test and evaluate the results of it.
