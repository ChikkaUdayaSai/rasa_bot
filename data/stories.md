## story 01
* greet
    - utter_greet
    
## story 02
* goodbye
    - utter_goodbye
    
## story 03
* inform
    - utter_ask_location
    
## story 04
* inform
    - action_weather        ## Generated Story -7556950119413069613
* greet
    - utter_greet
* inform
    - utter_ask_location
* inform{"location": "italy"}
    - slot{"location": "italy"}
    - action_weather
    - slot{"location": "italy"}
* goodbye
    - utter_goodbye

