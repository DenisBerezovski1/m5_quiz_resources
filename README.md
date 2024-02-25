## Урок 5. Ресурсы проекта
# Цель практической работы:
Применить знания:
• по созданию и добавлению ресурсов,
• по настройке AndroidManifest файла,
• по подключению gradle зависимостей.


## Что нужно сделать:

Практическая работа — первый этап в создании небольшого QUIZ-приложения, которым вы будете заниматься на протяжении нескольких модулей.

На этом этапе вам предоставлен шаблон приложения с логикой, ресурсами и архивом с файлами artifacts.zip. Нужно доработать проект: изменить некоторые параметры, импортировать ресурсы и настроить зависимости.

1. Придумайте осмысленное название для приложения и измените его app_name в строковых ресурсах.

2. Установите параметр minSdk так, чтобы он соответствовал версии Android 7.0.

3. Измените applicationId на вариант, который лучше подходит к названию вашего приложения.

4. Добавьте актуальную и стабильную версию библиотеки android.material в gradle-зависимости.

5. Подключите функцию View Binding в проект.

6. Добавьте новую иконку приложения с помощью конфигуратора иконок.

7. Измените цвета в основной теме приложения.

8. Создайте директорию Font, добавьте группу шрифтов Opensans из файла архива и установите этот шрифт для текста в основной теме приложения.

9. Добавьте два музыкальных WAV-файла из архива в проект. Выберите для этого подходящую директорию.

10. Добавьте разрешение для подключения «Интернет» в вашем манифест-файле.

11. Создайте первый экран в приложении — экран приветствия пользователя, с которого он уже будет переходить на главный экран викторины. На экране приветствия (если вы создали проект из шаблона Empty Views Activity, то это будет единственный экран вашего приложения на данный момент) добавьте изображение welcome_picture (представлено в архиве в векторном формате SVG) и кнопку «Продолжить».


