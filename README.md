# LabExam
Как разработчику программного обеспечения вам передали в доработку проект. Задача проекта - управление системой сетевых принтеров и печать на любом из них, посредством выбора нужного принтера и текстового файла для печати.

Ваша задача:
* проанализировать требования продукта
* доработать продукт до требуемой функциональности
* проанализировать существующий код и устранить потенциальные проблемные места
* покрыть код максимально юнит-тестами (создать новый проект при необходимости)
* разрешено вносить любые изменения в код, не ухудшающие его функциональность
* все внесенные изменения должны быть задокументированны и обоснованы (комментариями в коде)

Требования к ПО:
* система в виде консольного приложения
* все операции осуществляются посредством выбора пункта в меню
* добавление нового принтера в систему с указанием его имени и модели (должны быть уникальными)
* после добавления принтер становится доступным в списке
* печать текстового документа из выбранного файла на выбранном принтере (симуляция печати)
* логирование действий пользователя в файл (как в образце)
* определение момента начала и окончания печати через события
* система должна быть масштабируема и легко сопровождаться
