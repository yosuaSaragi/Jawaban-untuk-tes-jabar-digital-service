# Jawaban-untuk-tes-jabar-digital-service
query untuk jabar digital service


SELECT userid, 
AVG(duration) 
FROM sessions 
GROUP BY userid HAVING COUNT(userid) > 1;
