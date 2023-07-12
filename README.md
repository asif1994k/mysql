# mysql

CREATE DATABASE Bigdata;
use Bigdata
;
show databases; 
use Bigdata; 
create TABLE Employee(
    id int,
    name varchar(20),
     saralary BIGINT); 
     
create TABLE Employee(
    id int,
    name varchar(20),
     salary BIGINT);
     
 insert into Employee values(1,"rahul",10000);

 insert into Employee values(2,"kapil",20000);
 
 insert into Employee values(3,"naveen",40000)

 insert into Employee values(4,"kumar",50000)

select * from Employee LIMIT ;

select MAX(salary)from Employee where salary<(select MAX(salary) from Employee) LIMIT 0,100;
