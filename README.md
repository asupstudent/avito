Руководство по настройке и запуску проекта

1. Устанавливаем jdk-17_windows-x64_bin.exe (LTS) ссылка https://www.oracle.com/java/technologies/downloads/#jdk17-windows проверяем java --version
2. Скачиваем Maven apache-maven-3.9.5-bin.zip ссылка https://maven.apache.org/download.cgi проверяем mvn --version
3. Распаковываем apache-maven-3.9.5-bin.zip в удобную папку и прописываем apache-maven-3.9.5\bin в PATH
4. Для VSCode устанавливаем плагин Extension Pack for Java + все его зависимости
5. В VSCode (Explorer) появляется вкладка Maven
6. В вкладке Maven нажимаем + (воздаем проект)
7. Выбираем maven-archetype-quickstart
8. Версия 1.4 (последняя)
9. group id указываем com.asupstudent (группа моих проектов)
10. artifact id указываем avito название проекта (папка с проектом)
11. Указываем папку с проектом на диске
12. Скачивается все необходимое
13. По ходу установки указываем версию проекта 1.0
14. Проверяем все что мы задавали и подтверждаем Y
15. VSCode предложит открыть проект, открываем
16. Проект создан
17. Компилируем проект команда mvn compile
18. Собираем jar архив команда mvn package
19. Запуск команда java -cp .\target\avito-1.0.jar com.asupstudent.App
	-cp  (classpath) указываем, что классы нужно искать в jar файле, дополнительноу указываем com.asupstudent.App, где находится точка входа в приложение (метод main)
20. Получаем в консоли Hello World!
21. Для очистки проекта команда mvn clean
