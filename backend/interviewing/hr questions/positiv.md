Функционал прохождения собеседования
Пройти собеседование
Тестовые данные: http://79.137.204.102:8000/api/v1/hr-questions/
1.Создать новый запрос в Postman
2.Выбрать метод GET для Request
3.Ввести URL: http://79.137.204.102:8000/api/v1/hr-questions/
4.Query params 
Key - Page
Value - 1


Отправить Request
Ожидаемый результат: 200 ok
Response body

{
  "count": 3,
  "next": "http://79.137.204.102:8000/api/v1/hr-questions/?page=2",
  "previous": null,
  "results": [
    {
      "question": "Тестовый вопрос 1",
      "answer": "Тестовый ответ 1"
    }
  ]
}

Автор: Евгений

Тест выполнен

Дата	Время	Результат	Имя	Баг № Trello
2023-08-30	11:15	Passed	Юлия	-

Автор: Юлия
Тест выполнен
29.08.2023