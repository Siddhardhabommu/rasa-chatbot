## happy path
* greet
  - utter_greet
* inform_country
  - Answer_nationality
* nationality
  - utter_happy
* inform
  - Answer_fine
* mood_great
  - utter_happy
  - utter_goodbye

## sad path 1
* greet
  - utter_greet
* inform_country
  - Answer_nationality
* nationality
  - utter_happy
* inform
  - Answer_fine
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy


## sad path 2
* greet
  - utter_greet
* inform
  - Answer_fine
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_infromation

## say information
* informaton
  - utter_information

## bot challenge
* eligible
  - utter_eligible
