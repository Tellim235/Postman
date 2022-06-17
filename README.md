# Postman & JS

### HW_1 (Postman)

Создать запросы в Postman.

Protocol: http

IP: 162.55.220.72

Port: 5005

### EP_1

Method: GET

EndPoint: /get_method

request url params:
+ name: str
+ age: int

response: 
```JSON
[
    “Str”,
    “Str”
]
```
==================

### EP_2
Method: POST

EndPoint: /user_info_3

request form data: 
+ name: str
+ age: int
+ salary: int

response: 
```JSON
{'name': name,
          'age': age,
          'salary': salary,
          'family': {'children': [['Alex', 24], ['Kate', 12]],
                     'u_salary_1_5_year': salary * 4}}
```

==================

EP_3

Method: GET

EndPoint: /object_info_1

request url params: 
+ name: str
+ age: int
+ weight: int

response: 
```JSON
{'name': name,
          'age': age,
          'daily_food': weight * 0.012,
          'daily_sleep': weight * 2.5}
```

==================

EP_4

Method: GET

EndPoint: /object_info_2

request url params: 
+ name: str
+ age: int
+ salary: int

response: 
```JSON
{'start_qa_salary': salary,
          'qa_salary_after_6_months': salary * 2,
          'qa_salary_after_12_months': salary * 2.7,
          'qa_salary_after_1.5_year': salary * 3.3,
          'qa_salary_after_3.5_years': salary * 3.8,
          'person': {'u_name': [user_name, salary, age],
                     'u_age': age,
                     'u_salary_5_years': salary * 4.2}
          }
```

==================

EP_5

Method: GET

EndPoint: /object_info_3

request url params: 
+ name: str
+ age: int
+ salary: int

response: 
```JSON
{'name': name,
          'age': age,
          'salary': salary,
          'family': {'children': [['Alex', 24], ['Kate', 12]],
                     'pets': {'cat':{'name':'Sunny',
                                     'age': 3},
                              'dog':{'name':'Luky',
                                     'age': 4}},
                     'u_salary_1_5_year': salary * 4}
          }
```
==================

EP_6

Method: GET

EndPoint: /object_info_4

request url params: 
+ name: str
+ age: int
+ salary: int

response: 
```JSON
{'name': name,
          'age': int(age),
          'salary': [salary, str(salary * 2), str(salary * 3)]}
```

==================

EP_7

Method: POST

EndPoint: /user_info_2

request form data: 
+ name: str
+ age: int
+ salary: int

response: 
```JSON
{'start_qa_salary': salary,
          'qa_salary_after_6_months': salary * 2,
          'qa_salary_after_12_months': salary * 2.7,
          'qa_salary_after_1.5_year': salary * 3.3,
          'qa_salary_after_3.5_years': salary * 3.8,
          'person': {'u_name': [user_name, salary, age],
                     'u_age': age,
                     'u_salary_5_years': salary * 4.2}
          }
 ```


### HW_2 (JS)
 1. Создать переменную “item_1”
 2. Присвоить переменной item_1 цифру 5.
 3. Вывести в консоль item_1.
 4. Создать переменную “item_2”
 5. Присвоить переменной item_2 цифру 3.
 6. Вывести в консоль item_2.
 7. Создать переменную “item_3”
 8. Присвоить переменной item_3 сложение item_1 и item_2.
 9. Вывести в консоль item_3.
 10. Создать переменную “item_4”
 11. Присвоить переменной item_4 строку “Yolochka”
 12. Вывести в консоль item_4.
 13. Вывести в консоль сложение item_3 и item_4.
 14. Вывести в консоль умножение item_3 и item_4.
 15. Создать переменную “item_5”
 16. Присвоить переменной item_5 переменную item_3
 17. Создать переменную item_6.
 18. Создать переменную item_6_type
 19. Присвоить переменной item_6 значение 15
 20. Присвоить переменной item_6_type тип переменной item_6
 21. Вывести в консоль тип данных item_6 в виде ——  “item_6 == ”  item_6,  “item_6_type == ”  item_6_type ——  
 22. Создать переменную item_7 и в ней преобразовать item_6 в String.
 23. Создать переменную item_7_type
 24. Присвоить переменной item_7_type тип переменной item_7
 25. Вывести в консоль тип данных item_7 в виде ——  “item_7 == ”  item_7,  “item_7_type == ”  item_7_type ——  
 26. Создать переменную “age_1” и присвоить ей значение 10
 27. Создать переменную “age_2” и присвоить ей значение 18
 28. Создать переменную “age_3” и присвоить ей значение 60
 29. Создать if в котором будите проверять значение переменной age_1
 30. Если age_1 < age_2, вывести в консоль “You don’t have access cause your age is ” + age_1 + “ It’s less then ”
 31. Если age_1 >=  age_2 и age_1 <  age_3, вывести в консоль “Welcome  !”
 32. Если age_1  > age_3, вывести в консоль “Keep calm and look Culture channel”.
 33. Иначе выводите “Technical work”.
