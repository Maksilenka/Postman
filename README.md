#Работа в Postman
----------------------------------------------------------------------------------------------------------------------------------------------------------
Создать запросы в Postman.
Create new collection - New request

Protocol: http
IP: 162.55.220.72
Port: 5005

в поле "Enter request URL" вписать http://162.55.220.72:5005/ и нажать Save

EP_1
Method: GET
EndPoint: /get_method
request url params:
name: str
age: int

Переименовать "New Request" в "EP1"
1. Выбрать метод GET, в поле "Enter request URL" дописать "/get_method", чтоб получилось http://162.55.220.72:5005/get_method
2. выбрать "Params"
2.1. в столбец "KEY" добавить две строки с именами "name" и "age"
2.2. в столбец "VALUE" добавить значения "Lena" и "27" напротив ключей "name" и "age" соответственно
3. нажать Save и Send

response:
ответ

[
    "Lena",
    "27"
]
в поле "Enter request URL" будет отображаться URL http://162.55.220.72:5005/get_method?name=Lena&age=27

EP_2
Method: POST
EndPoint: /user_info_3
request form data:
name: str
age: int
salary: int

В коллекции создать "New Request" и переименовать его в "EP2"
1. Выбрать метод Post, в поле "Enter request URL" вписать http://162.55.220.72:5005/user_info_3
2. выбрать "Body" в нем "from-data"
2.1. в столбец "KEY" добавить три строки с именами "name", "age" и "salary"
2.2. в столбец "VALUE" добавить значения "Lena", "27" и "35000" напротив ключей "name", "age" и "salary" соответственно
3. нажать Save и Send

response:
ответ

{   
    "age": "27",
    "family": {"children": [["Alex", 24], ["Kate", 12]],
               "u_salary_1_5_year": 140000},
    "name": "Lena",
    "salary": 35000
}
в поле "Enter request URL" URL не изменяется

EP_3
Method: GET EndPoint: /object_info_1 request url params: name: str age: int weight: int

В коллекции создать "New Request" и переименовать его в "EP3"
1. Выбрать метод Get, в поле "Enter request URL" вписать http://162.55.220.72:5005/object_info_1
2. выбрать "Params"
2.1. в столбец "KEY" добавить три строки с именами "name", "age" и "weight"
2.2. в столбец "VALUE" добавить значения "Lena", "27" и "60" напротив ключей "name", "age" и "weight" соответственно
3. нажать Save и Send

response:
ответ

{
    "age": 27,
    "daily_food": 0.72,
    "daily_sleep": 150.0,
    "name": "Lena"
}
в поле "Enter request URL" будет отображаться URL http://162.55.220.72:5007/object_info_1?name=Lena&age=27&weight=60

EP_4
Method: GET
EndPoint: /object_info_2
request url params:
name: str
age: int
salary: int

В коллекции создать "New Request" и переименовать его в "EP4"
1. Выбрать метод Get, в поле "Enter request URL" вписать http://162.55.220.72:5005/object_info_2
2. выбрать "Params"
2.1. в столбец "KEY" добавить три строки с именами "name", "age" и "salary"
2.2. в столбец "VALUE" добавить значения "Polina", "12" и "10000" напротив ключей "name", "age" и "salary" соответственно
3. нажать Save и Send

response: ответ

{
    "person": {
        "u_age": 12,
        "u_name": ["Polina",10000,12],
        "u_salary_5_years": 42000.0
    },
    "qa_salary_after_1.5_year": 33000.0,
    "qa_salary_after_12_months": 27000.0,
    "qa_salary_after_3.5_years": 38000.0,
    "qa_salary_after_6_months": 20000,
    "start_qa_salary": 10000
}
в поле "Enter request URL" будет отображаться URL http://162.55.220.72:5005/object_info_2?name=Polina&age=12&salary=10000

EP_5
Method: GET
EndPoint: /object_info_3
request url params:
name: str
age: int
salary: int

В коллекции создать "New Request" и переименовать его в "EP5"
1. Выбрать метод Get, в поле "Enter request URL" вписать http://162.55.220.72:5005/object_info_3
2. выбрать "Params"
2.1. в столбец "KEY" добавить три строки с именами "name", "age" и "salary"
2.2. в столбец "VALUE" добавить значения "Kirill", "2" и "10" напротив ключей "name", "age" и "salary" соответственно
3. нажать Save и Send

response:
ответ

{
    "age": "2",
    "family": {"children": [["Alex", 24], ["Kate", 12]],
               "pets": {"cat": {"age": 3, "name": "Sunny"},
                        "dog": {"age": 4, "name": "Luky"}},
               "u_salary_1_5_year": 40},
    "name": "Kirill",
    "salary": 10
}
в поле "Enter request URL" будет отображаться URL http://162.55.220.72:5005/object_info_3?name=Kirill&age=2&salary=10

EP_6
Method: GET
EndPoint: /object_info_4
request url params:
name: str
age: int
salary: int

В коллекции создать "New Request" и переименовать его в "EP6"
1. Выбрать метод Get, в поле "Enter request URL" вписать http://162.55.220.72:5005/object_info_4
2. выбрать "Params"
2.1. в столбец "KEY" добавить три строки с именами "name", "age" и "salary"
2.2. в столбец "VALUE" добавить значения "Ivan", "22" и "2000" напротив ключей "name", "age" и "salary" соответственно
3. нажать Save и Send

response:
ответ

{
    "age": 22,
    "name": "Ivan",
    "salary": [2000, "40000", "6000"]
}
в поле "Enter request URL" будет отображаться URL http://162.55.220.72:5005/object_info_4?name=Ivan&age=22&salary=2000

EP_7
Method: POST
EndPoint: /user_info_2
request form data:
name: str
age: int
salary: int

В коллекции создать "New Request" и переименовать его в "EP7"
1. Выбрать метод Post, в поле "Enter request URL" вписать http://162.55.220.72:5005/user_info_2
2. выбрать "Body" в нем "from-data"
2.1. в столбец "KEY" добавить три строки с именами "name", "age" и "salary"
2.2. в столбец "VALUE" добавить значения "Tanya", "42" и "30000" напротив ключей "name", "age" и "salary" соответственно
3. нажать Save и Send

response:
ответ

{
    "person": {
        "u_age": 42,
        "u_name": ["Tanya",30000,42],
        "u_salary_5_years": 126000.0
    },
    "qa_salary_after_1.5_year": 99000.0,
    "qa_salary_after_12_months": 81000.0,
    "qa_salary_after_3.5_years": 114000.0,
    "qa_salary_after_6_months": 60000,
    "start_qa_salary": 30000
}
в поле "Enter request URL" URL не изменяется
