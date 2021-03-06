# Отчёт о тестировании Валидатора номеров банковских карт

## Краткое описание

11 марта 2021 года было проведено: функциональное тестирование приложения Валидатора номеров банковских карт

На тестирование затрачено: 0,5 часа

## В результате тестирования выявлены следующие дефекты:

1. [Валидатор карт не распознал номера карт American Express](https://github.com/tpecherkina/java12/issues/1)  
2. [Валидатор карт не распознал номера карт Diners Club](https://github.com/tpecherkina/java12/issues/2)  
3. [Валидатор карт не распознал номера карт Visa длинной менее 16 цифр](https://github.com/tpecherkina/java12/issues/3)  

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:  Исходный код программы

Тестовые данные: генератор номеров карт с сайта https://www.businessyeti.com/Apps/CreditCardGenerator/

American Express (15 digits)  
341111111111111  
American Express (15 digits)  
378282246310005  
American Express (15 digits)  
371449635398431  
American Express Corporate (15 digits)  
378734493671000  
Diners Club (14 digits)  
30569309025904  
Diners Club (14 digits)  
38520000023237  
Discover (16 digits)  
6011601160116611  
Discover (16 digits)  
6011111111111117  
Discover (16 digits)  
6011000990139424  
JCB (16 digits)  
3530111333300000  
JCB (16 digits)  
3566002020360505  
MasterCard (16 digits)  
5431111111111111  
MasterCard (16 digits)  
5555555555554444  
MasterCard (16 digits)  
5105105105105100  
Visa (16 digits)  
4111111111111111  
Visa (16 digits)  
4012888888881881  
Visa (13 digits)  
4222222222222  

## Тестирование производилось в следующем окружении:
1. Windows 10 64 bit
2. Java 11.0.10

