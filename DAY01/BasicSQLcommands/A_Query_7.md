# Question:
### Write the query to display the productionname, ownername who has not produced the ‘hindi’ movie.

# Query:
### select p.Productionname,p.Ownername from productions p left join movie m on m.Productionid=p.productionid and m.language="Hindi" where m.Language is null;

![Alt Text](https://github.com/rohini-kesireddy/MYSQL/blob/main/DAY01/Images/A_Query_7.png)<br />
