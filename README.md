# **MUSIC RECCOMENDATION**
- **Dataset** - https://www.kaggle.com/datasets/arjunvankani/recommendation-system-challenge-music-suggestion
- This Repository is about Music dataset and its reccomedations. We are making use of collaborative filtering methods on this dataset to find reccomendation.
- ## **Description**:
- Tables
  
**train.csv**

 • msno: user id
 
 
• song_id: song id

• source_system_tab: the name of the tab where the event was triggered.
 
• source_screen_name: name of the layout a user sees.
 
• source_type: an entry point a user first plays music on mobile apps. An entry point could
 be album, online-playlist, song .. etc.
 
• target: this is the target variable. target=1 means there are recurring listening event(s) triggered within
 a month after the user’s very first observable listening event, target=0 otherwise .

**test.csv**

• id: row id (will be used for submission)

• msno: user id

• song_id: song id

• source_system_tab: the name of the tab where the event was triggered.

• source_screen_name: name of the layout a user sees.

• source_type: an entry point a user first plays music on mobile apps. An entry point could
be album, online-playlist, song .. etc.

## **Exploratory Data Analysis**
- We have made use of 
  ## Methods and models implemented
  - We have made use of the item item collaborative filtering, k nearest neighbour algorithm and neural network for matrix factorization
  - In item item collaborative filtering involves calculating similarities between and item with the items previously consumed by users and then reccomending the most similar ones with the taste of the user.
  - K nearest neighbour algorithim is used to extract similar users form a group of users.
  - We are creating 2 neural networks, one for linear relations and the other for complex relations and then merging them to find the most appropriate items.
## Conclusions
-Accuracy for K nearest neighbour algorithm is coming out to be 69%.
## Collaborators
-


