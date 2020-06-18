HASHING is a data structure that is used to store a large number of data, which can be accessed in O(1) time by operations such as search, insert, delete.
- It is used to search a record efficiently.
-CollisionHandling:Since a hash function gets us a small number for a big key, there is a possibility that two keys might result in the same value. The situation where a newly inserted key maps to an already occupied slot in the hash table is called collision and must be handled using some collision handling technique. There are many ways to handle collisions.In this project the collision handling technique used is: Chaining:The idea is to make each cell of the hash table point to a linked list of records that have the same hash function value. Chaining is simple, but requires additional memory outside the table.
Requirements to run the code are:
- i) Python 3
- ii) Python IDE(recommended Spyder)
- iii) Pandas
- iv) CSV
- v) Time
How to run the code:
-1)Import the packages such as CSV,Time,Pandas
-2)Add your input and result file paths to the source_file_path and destination_file_path.
-3)Run the program and follow the instructions displayed on the console.
