## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy
* thank
  - utter_thank
  - utter_goodbye

## sad path 1
* greet
  - utter_greet
  - utter_help_you
* mood_unhappy
  - utter_cheer_up
  - utter_give_more_task
* affirm
  - utter_affirm
  - utter_give_more_task



## sad path 2
* deny
  - utter_deny
  - utter_give_more_task

## say goodbye
* goodbye
  - utter_byemsg
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot


## hospital path3
* location
  - utter_location
* contact
  - utter_contact
* services
  - utter_services
  - utter_choose_service
* heart
  - utter_heart
  - utter_did_that_help
* diabetes
  - utter_diabetes
  - utter_did_that_help
* obease
  - utter_obease
  - utter_did_that_help
