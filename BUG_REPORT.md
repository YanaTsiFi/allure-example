Описание найденного бага в Allure

Файл: Manual.java

Расположение: src/main/java/io/qameta/allure/annotations/

Ошибка:
Неправильное имя для метки ручных тестов в аннотации @Manual

Код с ошибкой:
@LabelAnnotation(name = "ALLURE_MANUAL", value = "true")

Правильный вариант:
@LabelAnnotation(name = "manual", value = "true")


