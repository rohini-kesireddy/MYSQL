# Question:
### Write the query to display productionid, production name with total number movies produced by each

# Query:
### select productions.Productionid, productions.Productionname, count(distinct movie.Moviename) as movie_count from productions inner join movie where productions.Productionid = movie.Productionid group by productions.Productionid;</br>

![Alt Text](https://github.com/rohini-kesireddy/MYSQL/blob/main/DAY01/Images/A_Query_1.png)<br />
