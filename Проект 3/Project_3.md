 Project Tasks : 
1. Develop a FAT for [ToDo List](https://sky-todo-list.herokuapp.com/)
2. Develop a Postman collection for FAT
3. Make a stub-object fot two operations in ToDo app:
   - A bulk of 3 or more tasks shall be received when a task list is requested.
   - The UUID of the new task shall be received when making a new task (for doing so we need to write down in the response body
     -  "id": "{{faker 'datatype.uuid'}}” — this line will inform Mockoon that the data generatory (datatype) is to be used and random UUID is to be inserted.
4. Add a rule for GET-query:
   - If the query contains the 'result' headline with 'empty list' value, then the stub element shall return the empty data bulk.
  ---
  Documentation for the project :
   - FAT (https://docs.google.com/spreadsheets/d/13p9S8zqcwzTZ3-FcWgr12GGeLUkLYaFfKDshi44NFpA/edit?usp=sharing )
  #### Postman collection :
-  Get a task list [List Tasks](https://drive.google.com/file/d/1I4ueDJA-Bxw7LRVYtp7tzsSSq6eeACMQ/view?usp=sharing/)
-  Add a task [Add Task](https://drive.google.com/file/d/13wl8FVoITrZ9T45Uu-FGtiIPCSuTdV8S/view?usp=sharing/)
-   Get task list [List_Tasks](https://drive.google.com/file/d/1K6gbeGpgRtn3VYOjGyiyqJf_38Piinek/view?usp=sharing/)
-   checking via UI [UI](https://drive.google.com/file/d/1s_Bzwl_wQGkfK-JMbe3jvoU8G7F1m0wf/view?usp=sharing/)
-   delete a task [Delete_Task](https://drive.google.com/file/d/1z0wcCS7JhY_ty9a1k3Vfq8Oy5qcgeqhy/view?usp=sharing/)
-   Get task list [List_Tasks](https://drive.google.com/file/d/1lGioLdKbrco8QxdeMxkANBLGQqoFoM9u/view?usp=sharing/)
-   checking via UI [UI](https://drive.google.com/file/d/10CLnNKQVXeA2Ogv4Zn0lx_4KNl6hrHI4/view?usp=sharing/)

#### Mockoon заглушки : 
- получение списка задач [List_Moc](https://drive.google.com/file/d/10bHfp29bhJ27_xhcFxO27BTBN8rIoYRi/view?usp=sharing/)
  - запрос в Postman [List_Mock](https://drive.google.com/file/d/13DLbyDxmVo020qoCtJsoob007qzTiUqI/view?usp=sharing/)
  - создание правила для GET запроса [Empty List](https://drive.google.com/file/d/1BKDiKT6Y-pp77cs4g8h2dma5Ozdh9LlI/view?usp=sharing) - для этого пропишем в  [Params:result, а в value:empty list](https://drive.google.com/file/d/1gCqCKXsNtyPqImtceIGCrMwOeRU5Q54R/view?usp=sharing)

