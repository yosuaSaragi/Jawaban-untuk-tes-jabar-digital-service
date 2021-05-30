# DE_SQL #1


SELECT userid, 
AVG(duration) 
FROM sessions 
GROUP BY userid HAVING COUNT(userid) > 1;
