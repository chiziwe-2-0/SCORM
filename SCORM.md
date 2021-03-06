## Отчет о создании пакета SCORM 1.2 в CourseLab 3
### Тема курса: **«PyPy: Python с JIT-интерпретатором»**

1. Основной слайд-заставка с темой и информацией об авторе:
![image_2021-12-13_23-58-33](https://user-images.githubusercontent.com/67209858/145910219-404c4a4e-cc53-41e8-a362-e5a16362b969.png)
2. Перейдем к созданию основных слайдов.  
Для первого слайда пропишем действие, устанавливающее **score=1**. По аналогии с ним установим для последующих 5 слайдов:
![image_2021-12-13_23-59-05](https://user-images.githubusercontent.com/67209858/145911691-d0a26166-562a-4dee-a6e3-ba77f4a99ffb.png)  
Т.е. за прохождение 1 слайда начисляется 1 балл, 2 слайда 2 балла, 3 слайда 4 балла, и т.д. по степеням двойки. Итог total=63 для 6 слайдов. 
3. Создадим слайд с тестом.  
Максимальное количество баллов = 100 - total, соответственно, укажем 37:
![image_2021-12-13_23-59-36](https://user-images.githubusercontent.com/67209858/145911917-852b6eb7-154e-4ce4-bea4-1f60b3344229.png)
4. Для финального слайда с результатами добавим подсчет итоговых баллов и сообщение об успешном/неуспешном прохождении курса:
![image_2021-12-14_00-00-19](https://user-images.githubusercontent.com/67209858/145912050-310ebd61-5b07-4c18-96af-87cd22a7e5e2.png)
5. Опишем следующие действия для финального слайда:
![image_2021-12-14_00-00-43](https://user-images.githubusercontent.com/67209858/145912110-5e8ee5e1-e676-41fc-b788-16f8c959df0e.png)
Таким образом, если количество баллов не меньше 85, то будет показано сообщение об успешном прохождении курса, а также будет установлен флаг успешного прохождения. Соответственно, при меньшем количестве итоговых баллов, курс будет не пройден.  
![image_2021-12-14_00-01-20](https://user-images.githubusercontent.com/67209858/145912266-b7be9e4e-b18e-4fee-82b1-30b05474aba2.png)


### Примеры

## Демонстрация успешного выполнения:
![do](https://user-images.githubusercontent.com/67209858/145906231-dcb01078-c36f-42f5-856a-aa6bff5ee666.gif)

## Демонстрация неуспешного выполнения:
![dont](https://user-images.githubusercontent.com/67209858/145906230-0b498287-41f6-438d-9d25-af5ea5e5b02f.gif)
