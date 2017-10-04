Interview Response

I created this program to test the complexity involved in processing each of SQL queries on my database. I have one table called Student and it has different cols and values. By using pgAdmin III, I was able to run 4 different SQL quiries.

SELECT * FROM students;    which used 1msec to be executed

SELECT *
FROM students
WHERE age > 22;           which used 13msec to be executed

SELECT *
FROM students
WHERE age > 19
OR first_name = 'Patric';        which used 13msec to be executed

SELECT *
FROM students
LIMIT 2;                  which used 14msec to be executed




