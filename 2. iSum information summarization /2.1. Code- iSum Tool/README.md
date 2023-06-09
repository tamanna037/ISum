# iSum Tool

### Liscence
The project is liscensed under MIT License, Copyright 2022 XXX. Get to know about the [liscense](https://github.com/tamanna037/InformationTypesDetectionNLP/blob/main/LICENSE) from here.

### Goal
Issue Summarizer (iSum) Tool detects the information types each sentence of a comment/post of a github issue is providng in order to support various software engineering activities.  The following 13 information types will be detected. 
1. Action on Issue
2. Bug Reproduction
3. Contribution and Commitment 
4. Expected Behaviour
5. Investigation and Exploration
6. Motivation 
7. Observed Bug Behaviour
8. Potential New Issues and Requests
9. Social Conversation 
10. Solution Discussion
11. Task Progress
14. Usage 
15. Workarounds


### How to run 
1. Clone the repository of the project and go tho folder of the repository.
2. In terminal, run the following commands.
3. First Install npm
   ```
      npm install
    ``` 
4. Create a virtual environment
   ```
    pip3 install virtualenv
    virtualenv newenv
    source newenv/bin/activate
    ```
5. Install other requirements
  ```
    pip3 install -r requirements.txt
   ```
6. Run the extension on localserver at port 8080
   ```
    python mysite/manage.py runserver
    
   ``` 

7. Visit chrome://extensions in your browser , Turn on Developer Mode,  Click Load Unpacked and Open the dist folder in the prompt that is displayed
8. Click on the extension button on your browser, select this extension and Input your github token. ![.](https://github.com/tamanna037/Issue-Discussion-Information-Type-Analytics-Tool/blob/main/img/token.png)
9. Go to any issue page to get the information type distribution and for now go to [IKVM](https://github.com/ikvm-revived/ikvm) repositry to get the project distribution.
