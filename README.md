Отчёт о тестировании **KeyValidator**    
Краткое описание    
**12.07.2021 - 12.07.2021** было проведено функционально тестирование приложения **KeyValidator**.

На тестирование затрачено: **1 час**

В результате тестирования выявлены следующие дефекты:     
**Валидные ключи**:

ОР: 80b427f8-92cd-3aae-ba04-3927fbe17c6 - вылидный
ОР: 387eedc6-12e9-3b32-9881-63b6b5e85317 - валидный     

ФР: 80b427f8-92cd-3aae-ba04-3927fbe17c6 - не вылидный
ФР: 387eedc6-12e9-3b32-9881-63b6b5e85317 - не валидный     

**Не валидные ключи**:    

ОР: 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 - не валидный    
ФР: 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 - вадидный          
**Описание процесса тестирования**
В процессе тестирования использовались следующие артефакты*:

git console

В качестве тестовых данных использовались данные:

[Задание](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

**Тестирование производилось в следующем окружении**

Ноутбук HP Pavilion,Windows 10, x64     
openjdk version "11.0.11" 2021-04-20

[issue 1](https://github.com/alexboom85/KeyValidator/issues/1)   
[issue 2](https://github.com/alexboom85/KeyValidator/issues/2)    
[issue 3](https://github.com/alexboom85/KeyValidator/issues/3)    
