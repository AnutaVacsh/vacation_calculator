# Калькулятор отпускных
Тестовое задание для учебного центра Neoflex 
  
Приложение "Калькулятор отпускных".  
Микросервис на SpringBoot + Java 11 c одним API:  
GET "/calculacte" 

## Cтек проекта
SpringBoot  
Java 11  
jUnit 
Mockito

## Usage
Запрос с указанием точного дня ухода в отпуск:  
```shell
http://localhost:8081/calculacte/40000/12.01.2024/12.02.2024
```
Response: 30034,13 
