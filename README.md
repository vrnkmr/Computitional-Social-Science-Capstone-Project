# Computitional-Social-Science-Capstone-Project
The project is consist from 4 parts:
- Web Scraping of videos from two YouTube channels
  Here I scraped data of videos (and recommended videos) from two American YouTube channels: Fox News and Breibat News. The first one is far-right one and the second one is even more right full of conspiracy theories. The scraped data you can find in the file "FoxNews_BreitbartNews_VeronikaMoroz"
- Analyze a social network with help of the software Gephi
  ![image](https://github.com/user-attachments/assets/40be2d35-9e44-4253-8975-34e22a1f6248)
Degree :  87,01% = 221 nodes has degree 1
12,2% = 31 nodes has degree 2
0,39% = 1 node has degree 126
0,39% = 1 node has degree 157

 In-Degree
87,01% = 221 nodes has in-degree 1
12,2% = 31 nodes has in-degree 2
0.79% = 2 nodes has in-degree 0

out-degree
99,24% = 252 nodes has out-degree 0 
0,39% = 1 node has our-degree 126
0,39% = 1 node has our-degree 157

What is the difference between them? 
degree -  Number of edges connected to a node, irrespective of direction.  
in-degree -  Number of edges directed into a node.  
out-degree -  Number of edges directed out of a node.  

Each number indicate the number of link which every node has. Two youtube surches  connected to the most other videos, however they have only out-degree but no in-degree. The videos in the center are shared videos by both surches, that is why they have two 

There are 31 recommended videos schares between two channels

Closeness centrality is an avarage path of one node to all other nodes. In my case it is:
0.36 for 126 nodes (purple - all videos from one channel)
0.33 for 95 nodes (light green - all videos from the othe channel)
0.5 for 14 nodes (blue - middle of the grapg, shared videos)
0.5 for 1 element ( orange - main central node - the channel up)
0,57 for 1 element  ( dark green - main central node - the other channel down)
![image](https://github.com/user-attachments/assets/6b364b66-2eea-44a6-a899-bcc6fb07bfa2)
![image](https://github.com/user-attachments/assets/4ae5d5b9-8fe3-4795-83d6-53696fabf34b)

  You can find a project in a file "project"
  
- Analyze the sentiment and emotions contained in the comment sections of the videos
Interesting fact is that a lot of shared videos between far-right and fascist channels were "cosy" videos with music, which is logical because everyone loves them. However, I could find two popular political videos, which will be interesting to analyse. 

1. https://www.youtube.com/watch?v=GioQp_j74eY - why Putin got into power
2. https://www.youtube.com/watch?v=hfJAgSOIWyc - news commenting  Trump`s second term
   You can find data in a file "youtube_comments_trump%2Bputin.xlsx"
   ![image](https://github.com/user-attachments/assets/0a013cb0-f986-43a4-a654-88716e74eee1)
Key Observations:

1. Both sets of comments express overwhelmingly negative sentiments about political leadership
2. The emotional profiles are remarkably similar despite different languages and
   a. specific political contexts
   b. The most striking similarity is the complete absence of joy
   c. Sadness and anger dominate both sets of comments
   d. The Russian comments show slightly more nuanced emotional depth, with a marginally more pronounced sense of historical pain
The parallel emotional landscapes suggest a universal human response to perceived political corruption and systemic betrayal, transcending specific cultural or linguistic contexts.
n my opinion, it is very precise analysis.
Sentiment - videos have very negative sentiment, for example " TOTAL DISGRACE!!  "
Sadness - both video comments express sadness. however, in the video about putin you can observe it more "  How painful! For parents who worked their whole lives  "
Anger - both have a pretty big level of anger, in Trump video it is a bit higher " FIRE HIM AND HIS CRONIES!"
Fear - there is more fear under video about trump " This IS A FIVE ALARM FIRE  "
Disgust - both videos have a medium level of disgust " The people do not exist for them  "
Joy  - no joy at all
Excitement - minimal excitement, however more under Trump video " FIRE HIM AND HIS CRONIES!  "

- Simulation on how ideas can diffuse into society
  I programmed artificial society to see how fast messages are spread if we have both media channels where people can pick up information. One source is smaller than another one, but more influential.
  In the results it turned out that doen`t matter how influential is source, the size is much more importang in spredding insormation.
  You can find the project in "Spread media in Society.nlogo"
  ![image](https://github.com/user-attachments/assets/962725c3-e837-4fbf-b131-bdad139af2ab)
![image](https://github.com/user-attachments/assets/7e4d428c-bcda-40b0-b088-4f5626c5a1bd)
![image](https://github.com/user-attachments/assets/4c1dfa92-2c34-410e-89f8-b5f17d5feefb)
