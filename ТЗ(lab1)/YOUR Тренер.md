 Министерство образования Российской Федерации

Московский государственный институт электронной техники

(технический университет)

Институт системной и программной инженерии и информационных технологий

утверждаю

Директор СПИНТех,

д.т.н., проф.\_\_\_\_\_\_\_Гагарина Л.Г.

«\_\_»\_\_\_\_\_\_\_\_\_2020 г.

Фитнес-приложение “YOUR Тренер”

Техническое задание на лабораторную работу

Листов 3

Руководитель, к.т.н., доцент\_\_\_\_\_\_\_\_Фёдоров А.Р.

Исполнитель, студент гр. ПИН-31

\_\_\_\_\_Егорова Ю.П.

 \_\_\_\_\_\_\_Ишков Г.А.

\_\_\_\_\_Кабиров М.В.

\_\_\_\_\_Киселева А.А

\_\_\_\_\_Макеева А.Д

**Зеленоград, 2020**

**1. Введение**

Работа выполняется в рамках учебного плана института СПИНТех НИУ “МИЭТ”. Настоящее техническое задание распространяется на разработку приложения для поддержания физической формы путем выполнения готовых тренировок и отслеживания прогресса. Создается с целью экономии времени и ресурсов пользователей. Приложение сможет предоставить альтернативу платным фитнес-тренировкам в спортзалах на выполнение упражнений, не выходя из дома.

**2. Наименование и область применения**

Приложение “YOUR Тренер” для поддержания физической формы, предназначенное для людей, желающих повысить свою физическую подготовку, не покидая дома.

**3. Основание для разработки**

3.1. Программа разрабатывается на основе учебного плана института СПИНТех НИУ “МИЭТ”.

3.2. Наименование работы Фитнес-приложение “YOUR Тренер”

3.3. Исполнители: “Team”

3.4. Соисполнители: нет.

 **4. Назначение разработки**

Приложение предназначено для использования людьми разного возраста при выполнении комплекса упражнений в целях поддержания тонуса и спортивного телосложения.

-    Приложение должно содержать меню-бургер:

    -   Тренировка;

    -   Статистика;

    -   Настройка;

-    Программа должна иметь простой и доступный интерфейс;
-    Приложение должно содержать в разделе меню “Тренировка”:

    -   Утренняя зарядка;

    -   Интенсивная кардио-тренировка;

    -   Круговая силовая тренировка;

    -   Растяжка;

-    Приложение должно содержать в каждом разделе подпункты:

    -   Уровень - LITE;

    -   Уровень - MEDIUM;

    -   Уровень - HARD;

-    Данное приложение должно вести подсчет по времени каждого упражнения и давать время на отдых после тренировок.
-   После начала упражнения будут доступны кнопки:

    -   ПАУЗА;

    -   ПРОПУСТИТЬ;

-   Между упражнениями предусмотрен отдых.
-   После упражнения переход на завершающую статистику и представлен выбор:

    -   Завершить тренировку;

    -   Выбор другой тренировки;

-   В разделе “Цели” показана статистика по выполненным тренировкам.
-   В разделе “Настройки”:

    -   Управление звуком;

    -   Настройка уведомлений;

Первоначальная версия приложения предусматривает 12 тренировок.

4.1. Требования к функциональным характеристикам

4.1.1. Программа должна обеспечивать возможность выполнения следующих функций:

-   выбор вида и уровня тренировки;
-   поддержка функционала в оффлайн-режиме
-   в каждом подразделе имеется gif /видео с инструкцией по упражнению;
-   таймер на выполнение каждого упражнения;
-   предоставление отчета после каждой тренировки в виде инфографики:

    -   Вид тренировки, уровень

    -   Время тренировки

    -   Количество сброшенных калорий(вычисляется по формуле)

    -   Настроение пользователя после тренировки

-   служба поддержки

    -   Сообщение об ошибке для техподдержки

    -   Обратная связь(отзывы, предложения, сотрудничество)

4.1.2. Исходные данные:

-   вес, рост, пол;
-   выбор подходящего вида и уровня тренировки;
-   видеоматериалы упражнений

4.1.3. Организация входных и выходных данных:

Входные данные поступают с клавиатуры, видеоматериалы хранятся на устройстве

Выходные данные отображаются на экране.

4.2. Требования к надежности:

Предусмотреть методы восстановления после отказа.

4.3. Требования к эксплуатации:

Смартфон на платформе Android 8.0 и выше.

Для успешной установки приложения устройство должно иметь минимальные технические характеристики, включая версию и объём оперативной памяти.

4.4. Требования к составу и параметрам технических средств

Система должна работать на Android-смартфонах.

Android не младше 8.0 / 8.1 Oreo

Минимальное количество свободного места на устройстве - 150 Мб

Минимальное количество оперативной памяти - 512 Мб

4.5. Требования к информационной и программной совместимости:

Для корректного функционирования приложения необходимо наличие операционной системы Android 8.0 и выше. Язык интерфейса – русский. Приложению требуются входные и выходные данные.

4.6. Требования к транспортировке и хранению:

Транспортировка программного продукта не предусматривается. Получение пользователем исключительно через PlayMarket.

 4.7. Специальные требования

4.7.1 программное обеспечение должно иметь дружественный интерфейс, рассчитанный на любого пользователя;

4.7.2 документация на ПО должна содержать полную информацию, необходимую для работы программистов с ним;

 4.7.3 язык программирования – по выбору исполнителя, должен обеспечивать возможность интеграции программного обеспечения с Android-смартфонами.

**5. Требования к программной документации:**

-   Разрабатываемые программные модули должны быть самодокументированы, т. е. тексты программ должны содержать все необходимые комментарии.
-   Состав программной документации должен включать в себя техническое задание;

<!-- -->

-   Разрабатываемая программа должна включать справочную информацию о разработчиках;

<!-- -->

-   В состав сопровождающей документации должны входить:

    -   Пояснительная записка, содержащая описание разработки;

    -   Руководство пользователя;

 **6. Технико-экономические показатели**

Первоначально предусматривается бесплатная версия приложения. В дальнейшем предусмотрено дополнение платным контентом.

**7. Порядок контроля и приемки**

После передачи Исполнителем отдельного функционального модуля программы Заказчику, последний имеет право тестировать модуль в течении 2 часов. После тестирования Заказчик должен принять работу по данному этапу или в устном виде изложить причину отказа принятия. В случае обоснованного отказа Исполнитель обязуется доработать модуль.

**8. Календарный план работ**

	Название этапа
	Сроки этапа
	Чем заканчивается этап
	
	Изучение предметной области. Продумывание идеи. Обсуждение и проработка приложения.
	01.09.2020-24.09.2020
	Сдача ТЗ приложения.
	
	Проектирование UML модели. Рефакторинг.
	08.09.2020-24.10.2020
	Готовые диаграммы: использования, последовательности, активности, классов, UseCase
	
	Выбор платформы реализации приложения.
	24.09.2020-08.10.2020
	Перечень используемых технологий. Декомпозиция системы. Готовый список необходимых задач порядок их выполнения(приоритет)
	
	Выбор модели ЖЦ. Кодирование и отладка ПО.
	08.10.2020-22.10.2020
	Составления этапов проектов в соответствии с ЖЦ. Доработка проекта.
	
	Тестирование ПО.
	22.10.2020-05.11.2020
	Проверка приложения в соответствии со всеми техниками тест-дизайна
	
	Unit-тестирование.
	05.11.2020-19.11.2020
	Анализ покрытия кода в модульных тестах.
	
	Экономический
	19.11.2020-03.12.2020
	Оценка ПО в соответствии с методом функциональных точек. Сравнение с реальным размером ПО.
	
	Приёмка.
	03.12.2020-31.12.2020
	Презентация готового продукта.
	

Руководитель работ Федоров А. Р..
