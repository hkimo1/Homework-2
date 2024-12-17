# Homework-2 
Part a)
1.What were your considerations when creating this test-data?

When creating the test data, my key considerations were: Ensuring the data structure closely mirrored the real dataset (u.datafile), including columns for user_id, movie_id, rating and timestamp.

2. were there cetain characteristics of the real data and file format that you made sure to capture in your test data?
   
Yes, the test data i created accurately reflected the following characteristics of the real dataset:
•	The test data was formatted as tab-separated values (\t), aligning with the u.data file format.
•	The first three columns captured user_id, movie_id, and rating, consistent with the actual dataset, while excluding the timestamp column=0.
•	The user_id and movie_id values were realistic integers, and the rating values were within the expected range (1 to 5).

3.Did you create a refrence solution for your test data? if so, how?

Yes, I created a reference solution using a smaller, manually calculated dataset:I used a small subset of the test data to manually compute similarity scores using the same formula as in the implementation.
