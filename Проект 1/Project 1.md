Задача: Провести тестирование новой функции в календаре в кабинете учителя на портале Skyeng

Как решал задачу:

Провел анализ стейкхолдеров, на основе основных пользовательских сценариев составил приемочные тест-кейсы; после чего составил общий тест-план в Confluence с указанием видов, сроков тестирования; провел декомпозицию продукта, подготовил чек-листы в Checkvist по функциональному тестированию, регрессиононному тестированию, провел тестирование требований продукта, составил тест-кейсы в qase.io по приемочному и smoke тестированиям, создал Postman-коллекцию, провел test-run, завел баги в баг-трекинговой системе Jira, подготовил отчет по тестированию в Confluence.
- ##### [ТЕСТ ПЛАН ПРОЕКТА]
(https://github.com/teresant2022/anton.tereshchenko/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%201/Test%20Plan_1.jpg)
(https://github.com/teresant2022/anton.tereshchenko/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%201/Test%20Plan_2.jpg)
(https://github.com/teresant2022/anton.tereshchenko/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%201/Test%20Plan_3.jpg)

- Шаг 1. Знакомство с требованиями: [Здесь](https://skyengpublic.notion.site/6746e543d02c43879de0057cafe196b0/) я познакомился с требованиями к функционалу «Личные события» на вкладке «Расписание». 
 - Шаг 2.  Узнал, кем явлются основные пользователи нашей системы, чтобы понять, какие приемочные тест-кейсы написать. Ознакомился с [описанием наших стейкхолдеров](https://github.com/Igor-Maltcev/QA-tester/blob/main/Project_1/userstory.PNG/)
  И на основании этих данных сдел [3 приемочных тест кейса](https://github.com/Igor-Maltcev/QA-tester/blob/main/Project_1/%D0%9F%D1%80%D0%B8%D0%B5%D0%BC.%D0%A2%D0%9A.PNG) по 1 для каждого стейкхолдера.
 - Шаг 3. Тестирование требований. Далее я протестировал требования, используя для этого критерии качественных требований.
 Данные занес в [таблицу](https://github.com/Igor-Maltcev/QA-tester/blob/main/Project_1/%D0%A2%D0%B5%D1%81%D1%82%D0%A2%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B9.PNG/)
 - Шаг 4. Сделал [декомпозицию продукта](https://miro.com/app/board/uXjVPpH2rmY=/) с помощью интерактивной доски Миро.
 - Шаг 5. Тест-план. Ну и на пятом шаге я собственно уже и составил   [Тест план](https://github.com/Igor-Maltcev/QA-tester/blob/main/Project_1/%D0%A2%D0%B5%D1%81%D1%82%D0%BF%D0%BB%D0%B0%D0%BD.PNG) как я буду проводить тестирование данного родукта.

---
- ##### ПОДГОТОВКА [ТЕСТОВОЙ ДОКУМЕНТАЦИИ](https://github.com/Igor-Maltcev/QA-tester/blob/main/Project_1/%D0%A2%D0%B5%D1%81%D1%82%D0%94%D0%BE%D0%BA.PNG/) : 
 - Шаг 1. Составил [функциональный чек-лист](https://github.com/Igor-Maltcev/QA-tester/blob/main/Project_1/%D1%81%D0%BE%D0%B1%D1%8B%D1%82%D0%B8%D1%8F-export.rar) для новой функции (личные события) в сервисе Sitechco
 - Шаг 2. Состаил  3 тест-кейса для [smoke-тестирования](https://github.com/Igor-Maltcev/QA-tester/blob/main/Project_1/Smoke.PNG/). Так как этот вид тестирования покажет, а стоит ли вообще проводить дальнейшее тестирование продукта.
  Ведь если smoke тесты зайфелятся, то дальнейшее тестирование не проводится.
  
  ---
  
 - ##### ТЕСТИРОРВАНИЕ :
  Ну и собственно на этом этапе и началось тестирование. [Было проведено](https://github.com/Igor-Maltcev/QA-tester/blob/main/Project_1/smok_cheklist.PNG/) smok тестирование,
  Функциональное тестирование по Чек листу. Приемочное тестирование функционала.
  По результатам test-run были заведены [баг репорты](https://github.com/Igor-Maltcev/QA-tester/blob/main/Project_1/%D0%91%D0%B0%D0%B3%D0%B8.PNG/) в баг трекинговой системе JIRA.
  
  ---
  
- ##### [ОТЧЕТ О ТЕСТИРОВАНИИ](https://github.com/Igor-Maltcev/QA-tester/blob/main/Project_1/%D0%9E%D1%82%D1%87%D0%B5%D1%82.PNG) :
На этом шаге была составлена подробная отчетная документация. Такая как : [сроки проведения работ](https://github.com/Igor-Maltcev/QA-tester/blob/main/Project_1/%D0%A1%D1%80%D0%BE%D0%BA%D0%B8_%D1%80%D0%B0%D0%B1%D0%BE%D1%82.PNG/), [команда тестировщиков](https://github.com/Igor-Maltcev/QA-tester/blob/main/Project_1/%D0%9A%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D0%B0.PNG/), [метрики](https://github.com/Igor-Maltcev/QA-tester/blob/main/Project_1/%D0%BC%D0%B5%D1%82%D1%80%D0%B8%D0%BA%D0%B8.PNG/) и отчетность.В том числе распределение найденых [дефектов](https://github.com/Igor-Maltcev/QA-tester/blob/main/Project_1/%D0%B4%D0%B5%D1%84%D0%B5%D0%BA%D1%82%D1%8B.PNG/) по атрибуту [Серьезность](https://github.com/Igor-Maltcev/QA-tester/blob/main/Project_1/%D0%A1%D0%B5%D1%80%D1%8C%D0%B5%D0%B7%D0%BD%D0%BE%D1%81%D1%82%D1%8C.PNG/).
 Дано [общее заключение о готовности продукта к релизу. Рекомендации](https://github.com/Igor-Maltcev/QA-tester/blob/main/Project_1/%D0%98%D1%82%D0%BE%D0%B3.PNG)
 
