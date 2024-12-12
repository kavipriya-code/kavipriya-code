'''
create table employees (
						id SERIAL primary key,
						name VARCHAR(100) NOT null,
						department varchar(50),
						salary numeric(10,2),
						hire_date DATE default CURRENT_DATE 
						);
      
insert into employees(name,department,salary)
			values
			('John Doe','HR',50000),
			('Jane Smith','Engineering',75000),
			('Mike Johnson','Marketing',70000);
		
commit;
			
select * from employees;
delete from employees where id=4;
delete from employees where id=5;
delete from employees where id=6;
'''
