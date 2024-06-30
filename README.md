create table products(Name varchar(20), Description varchar(20), Price int, Quantity int, Category varchar(20));
insert into products values('Stapler', 'Office', 200, 1, 'Stationery');
insert into products values('Desk', 'Wood', 5000, 1, 'Furniture');
insert into products values('Chair', 'Plastic', 1000, 2, 'Furniture');
select* from products;
select* from products where Price<1000;
select* from products where Quantity>1;
update products set Price=300 where Name='Stapler';
delete from products where Name='Stapler';
