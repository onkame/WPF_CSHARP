# WPF_CSHARP
TestSTP.sql - скрипт для создания БД компании Софт Трейд Плюс.
WpfApp2 - папка с проектом WPF-приложения, язык C#, создан в Visual Studio 2019.

Содержит 4 окна:
	1. MainWindow - главное меню, выбор таблиц для отображения и редактирования.
  	2. Window1 - окно редактирования и отображения данных таблицы Manager БД TestSTP. Отображение и редактирование осуществлено 
	согласно требованиям ТЗ как в этом пункте, так и в прочих
  	3. Window2 - окно редактирования и отображения данных таблицы Client БД TestSTP, реализован фильтр для отображения клиентов 
	по менеджерам и клиентов по статусам.
	4. Window3 - окно редактирования и отображения данных таблицы Product БД TestSTP, реализован фильтр для отображения товаров 
	по клиентам.

Процесс редактирования описан непосредственно в окнах Window1-3. 
Использование фильтра:
	1. Выбор данных для отображения по принадлежности к имеющимся в ComboBox;
	2. Нажатие кнопки "Отобразить";
	3. По окончании просмотра нажать кнопку "Снять фильтры" для возвращения исходного вида таблицы.
  
