create table customers(
customer_id char(7) , 
first_name varchar(15) not null,  
last_name varchar(15) not null,
city varchar(15) not null,
mobile_no char(10) not null,
pancard_no varchar(15),
constraint PK_customer PRIMARY KEY(customer_id));
