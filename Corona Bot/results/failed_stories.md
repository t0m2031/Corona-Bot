## happy path 1 (C:\Users\SSG\AppData\Local\Temp\tmpkmvcpv8c\23028311d3f646029984d017daf30fe7_conversation_tests.md)
* greet: hello there!
    - utter_greet   <!-- predicted: utter_did_that_help -->
* mood_great: amazing   <!-- predicted: bot_challenge: amazing -->
    - utter_happy   <!-- predicted: utter_iamabot -->


## happy path 2 (C:\Users\SSG\AppData\Local\Temp\tmpkmvcpv8c\23028311d3f646029984d017daf30fe7_conversation_tests.md)
* greet: hello there!
    - utter_greet   <!-- predicted: utter_did_that_help -->
* mood_great: amazing   <!-- predicted: bot_challenge: amazing -->
    - utter_happy   <!-- predicted: utter_iamabot -->
* goodbye: bye-bye!
    - utter_goodbye   <!-- predicted: utter_did_that_help -->


## sad path 1 (C:\Users\SSG\AppData\Local\Temp\tmpkmvcpv8c\23028311d3f646029984d017daf30fe7_conversation_tests.md)
* greet: hello
    - utter_greet   <!-- predicted: utter_did_that_help -->
* mood_unhappy: not good   <!-- predicted: negative: not good -->
    - utter_cheer_up   <!-- predicted: utter_negative -->
    - utter_did_that_help   <!-- predicted: action_listen -->
* affirm: yes   <!-- predicted: positive: yes -->
    - utter_happy   <!-- predicted: utter_positive -->


## sad path 2 (C:\Users\SSG\AppData\Local\Temp\tmpkmvcpv8c\23028311d3f646029984d017daf30fe7_conversation_tests.md)
* greet: hello
    - utter_greet   <!-- predicted: utter_did_that_help -->
* mood_unhappy: not good   <!-- predicted: negative: not good -->
    - utter_cheer_up   <!-- predicted: utter_negative -->
    - utter_did_that_help   <!-- predicted: action_listen -->
* deny: not really   <!-- predicted: negative: not really -->
    - utter_goodbye   <!-- predicted: utter_negative -->


## sad path 3 (C:\Users\SSG\AppData\Local\Temp\tmpkmvcpv8c\23028311d3f646029984d017daf30fe7_conversation_tests.md)
* greet: hi
    - utter_greet   <!-- predicted: utter_did_that_help -->
* mood_unhappy: very terrible   <!-- predicted: corona_intro: very terrible -->
    - utter_cheer_up   <!-- predicted: utter_corona_intro -->
    - utter_did_that_help   <!-- predicted: action_listen -->
* deny: no   <!-- predicted: negative: no -->
    - utter_goodbye   <!-- predicted: utter_negative -->


## say goodbye (C:\Users\SSG\AppData\Local\Temp\tmpkmvcpv8c\23028311d3f646029984d017daf30fe7_conversation_tests.md)
* goodbye: bye-bye!
    - utter_goodbye   <!-- predicted: utter_did_that_help -->


