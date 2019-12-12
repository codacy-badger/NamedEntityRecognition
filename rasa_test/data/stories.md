## happy path
* greet
  - action_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - action_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - action_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## affirmative
* affirmative
  - utter_affirm

## name recognition
* name_recognition
  - action_greet
  - utter_name
* provide_name
  - utter_repeat

