# Assignment 9

```sql
select customers.customerName, offices.city as office_city
from customers, employees, offices
where 
	customers.salesRepEmployeeNumber = employees.employeeNumber and 
	employees.officeCode = offices.officeCode and
    customers.city = offices.city;
```

## 1. Rewrite it as an expression in relational algebra

![Formula](https://raw.githubusercontent.com/kagejohn/db_assignment_09/master/LaTeX_formula/1.gif)

## 2. Add row counts to the subexpressions

![Formula](https://raw.githubusercontent.com/kagejohn/db_assignment_09/master/LaTeX_formula/2.gif)

## 3. Rewrite to a better expression

TODO
