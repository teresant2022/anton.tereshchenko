 Задачи проекта : 
1. Составить приемочный тест - кейс для продукта [ToDo List](https://sky-todo-list.herokuapp.com/)
2. Составить коллекцию в Postman для приемочного ТК
3. Создать заглушку для двух операций Todo-приложения:
   - На получение списка  задач должен возвращаться массив из 3 и более задач.
   - На создание задачи  должен возвращаться UUID новой задачи ( для этого нам надо прописать в тело ответа 
     -  "id": "{{faker 'datatype.uuid'}}” — эта строка сообщит Mockoon, что нужно  использовать генератор данных (datatype) и подставить рандомный UUID.
4. Добавить правило для GET-запроса:
   - Если в запросе был передан заголовок result со значением empty list, заглушка должна вернуть пустой массив.
  ---
  Документация проекта :
   - Приемочный [тест - кейс](https://docs.google.com/spreadsheets/d/13p9S8zqcwzTZ3-FcWgr12GGeLUkLYaFfKDshi44NFpA/edit?usp=sharing )
  #### Postman collection :
-  получить список задач   [List Tasks](https://drive.google.com/file/d/1I4ueDJA-Bxw7LRVYtp7tzsSSq6eeACMQ/view?usp=sharing/)
-  добавить задачу [Add Task](https://drive.google.com/file/d/13wl8FVoITrZ9T45Uu-FGtiIPCSuTdV8S/view?usp=sharing/)
-  получить список задач [List_Tasks](https://drive.google.com/file/d/1K6gbeGpgRtn3VYOjGyiyqJf_38Piinek/view?usp=sharing/)
-   проверить через [UI](https://drive.google.com/file/d/1s_Bzwl_wQGkfK-JMbe3jvoU8G7F1m0wf/view?usp=sharing/)
-   удалить задачу [Delete_Task](https://drive.google.com/file/d/1z0wcCS7JhY_ty9a1k3Vfq8Oy5qcgeqhy/view?usp=sharing/)
-   получить список задач [List_Tasks](https://drive.google.com/file/d/1lGioLdKbrco8QxdeMxkANBLGQqoFoM9u/view?usp=sharing/)
-   проверить через [UI](https://drive.google.com/file/d/10CLnNKQVXeA2Ogv4Zn0lx_4KNl6hrHI4/view?usp=sharing/)

#### Mockoon заглушки : 
- получение списка задач [List_Moc](https://drive.google.com/file/d/10bHfp29bhJ27_xhcFxO27BTBN8rIoYRi/view?usp=sharing/)
  - запрос в Postman [List_Mock](https://drive.google.com/file/d/13DLbyDxmVo020qoCtJsoob007qzTiUqI/view?usp=sharing/)
  - создание правила для GET запроса [Empty List](https://drive.google.com/file/d/1BKDiKT6Y-pp77cs4g8h2dma5Ozdh9LlI/view?usp=sharing) - для этого пропишем в  [Params:result, а в value:empty list](https://drive.google.com/file/d/1gCqCKXsNtyPqImtceIGCrMwOeRU5Q54R/view?usp=sharing)

