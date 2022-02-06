# Tips

#### 1. Adding pre-commit hooks to your github project.
**Follow the below steps: **

a. Add a .pre-commit-config.yaml file to your repo. (I have uploaded in this repo the standard .pre-commit-config.yaml file I use for my python projects.)

b. run pre-commit install. (Incase the terminal doesn't identify the pre-commit command, install it using python3 -m pip install pre-commit)

We are done!! You can commit your changes to your global repo as before except this time, your code will be much more polished.

# Project Ideas

#### 1. Predict if two drafts are written by the same person.
 
   **Challenges** - 
   
   a. Are people's writing styles distinct enough to distinguish them.
   
   b. Factors like time, mood etc can influence a person's writing style.
   
   c. Dissimilar genres of the two drafts.
   
   **Datasets** -
   
   Novels, Newspaper articles, Blogs etc.
   
   **Extension to this problem** - 
   
   How about predicting the artist based on paintings or cartoons etc.
   
#### 2. Language translator from sanskrit to related languages like Hindi.

      **Motivation** -
      
      Since most of the original ancient Hindu scriptures like Upanishads and Vedas were written in Sanskrit,
      Sanskrit to English translation will help understand them. 
      Though many translated works are available today, few people are interested in following the original scriptures.

#### 3. Automated 3-address code generator for programming languages.

#### 4. Convert image to text / speech to text.

#### 5. Extract tables from a pdf to excel sheet.

#### 6. Suitable title suggester for a given a draft.

# Questions

#### 1. Give your take on these two scenarios:

**Scenario-1** - 

You trained an LSTM model, it's training curve came out to be a horizonal line.

**Scenario-2** - 

You trained an LSTM model, it's training curve has an upward trend.
