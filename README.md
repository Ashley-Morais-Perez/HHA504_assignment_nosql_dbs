 # HHA504_assignment_nosql_dbs

 ## GCP ## 

 I loaded the patient data into Big Query and displayed the table
  <img width="947" alt="image" src="https://github.com/user-attachments/assets/dff0f591-7920-4d8a-996e-09e82c75c753">

I ran the table with query for selecting patients over 40 
<img width="947" alt="image" src="https://github.com/user-attachments/assets/330d9dfa-65c6-4a75-8245-2095d1959b83">

After reading the job description, it seems that 10 MB is going to be billed to the account
<img width="259" alt="image" src="https://github.com/user-attachments/assets/264d5f63-77a2-4dd9-b4be-10c4e3f31002">


## MongoDB Atlas

There was an issue connecting the MongosDB project to Compass. Intially I thought it was because I hadn't input the correct password format but that didn't seem to fix the issue at all. 

<img width="698" alt="image" src="https://github.com/user-attachments/assets/5d51b1c0-0398-4b27-a4c2-1eaf97d37079">

The only information it gave me was that the authentication failed. I tried creating a new connection but it still failed with the same error message.

<img width="479" alt="image" src="https://github.com/user-attachments/assets/0d01f5ca-e678-49e4-aee4-bb94831a7fe1">

Even in python (using Google Colab), the connection failed to MongosDB. The code after is just the template used to convert the CSV file to JSON, which worked as it required no connection to the MongosDB. 

<img width="833" alt="image" src="https://github.com/user-attachments/assets/0303208d-71be-472d-849f-c4b6abdd7159">

I got a more detailed error message explanation when trying to insert the file, knowing it wouldn't work as it hadn't connected in the first place. 

<img width="767" alt="image" src="https://github.com/user-attachments/assets/3f7eaa49-c92f-4d81-bf82-eb8bf8b73b00">

Even in Mongos, I must have missed an error in some configuration because I also received error messages just from trying to load sample data into Mongos Atlas. 

<img width="527" alt="image" src="https://github.com/user-attachments/assets/f8d2a06c-694d-46df-aa33-85beffd805e2">


## Redis ##

I was able to connect to Redis Insight much more easily by downloading the program and selecting the 'open with RedisInsight' button. Initially, I had tried entering the information manually but there seemed to be an error with whatever I was entering. Once I clicked this option, the database automatically connected on Redis Insignt. 

<img width="265" alt="image" src="https://github.com/user-attachments/assets/7c11ed39-ffcc-4253-9e33-d7e904762baa">

<img width="940" alt="image" src="https://github.com/user-attachments/assets/1439b7cd-f6db-4aea-947b-22f7f1e62e7b">

After using the sample code from the HW assignment instructions, the connection worked but I couldn't tell in the RedisInsight program if any data had been pushed 

<img width="682" alt="image" src="https://github.com/user-attachments/assets/2c75524e-3683-46c8-bf41-9d732d6160b5">

I used the Redis Query to see if I could pull any info from the Key but all I kept getting were null responses. The example provided with the bicycles wasn't the best help ( at least for me) since an error message would appear stating 'Invalid Field Type'

<img width="941" alt="image" src="https://github.com/user-attachments/assets/2a8dd244-c289-43ae-b3da-31131a7794b3">

<img width="734" alt="image" src="https://github.com/user-attachments/assets/5a4d9f0b-a518-42bd-818c-39e589b94457">

## Overall Experience ##

I think Redis and MongoDB are user-friendly since they offer tips and tutorials on navigating the program. However, I wish the error messages on MongosDB could be clearer on what information is incorrect or missing. For Redis, the examples given could have been shorter or at least with pre-defined indexes in order to have a better understanding of the commands used in their query. 

