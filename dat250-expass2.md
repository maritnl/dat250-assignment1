# Software Technology Experiment 2

## Technical problems

I experienced no technical problems during installation. Doing part 1 of the experiment I first tried following the de vogella tutorial, however I encountered some issues with getting the persistence library/jar to work, and as I use intelliJ it wasnt ideal to follow a tutorial based on Eclipse. Thus I made the switch to rather using the Maven project provided and had no further issues. 

## Code

The code for the experiments can be found [here](https://github.com/maritnl/dat250-assignment2/tree/master/eclipselink).

## Database

I inspected the database directly using [ij](https://db.apache.org/derby/papers/DerbyTut/ij_intro.html) through the terminal. To inspect what tables were created I used the 

```
show tables
```
command. 

I could further inspect the tables by using SQL statements. For example

```
select * from bankdb;
```

The tables for each experiment can be seen underneath. 
![Tables experiment1](images/exp1-tables?raw=true)
![Tables experiment2](images/exp2-tables?raw=true)


