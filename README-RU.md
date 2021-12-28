# Исправление стилистических ошибок в приложении "Hello, world!"

Задача начального уровня для практики навыка управления задачами в AutoCode. Переводы: [Английский](README.md).


## Заберите проект

* [Откройте проект в Visual Studio из внешнего Git-репозитория](https://docs.microsoft.com/ru-ru/visualstudio/get-started/tutorial-open-project-from-repo) или [склонируйте внешний Git-репозиторий на Ваш локальный диск](https://docs.microsoft.com/ru-ru/azure/devops/repos/git/clone#clone-from-another-git-provider) при помощи Visual Studio.


## Завершите задачу

1. [Соберите решение](https://docs.microsoft.com/ru-ru/visualstudio/ide/building-and-cleaning-projects-and-solutions-in-visual-studio).
    * Выберите элемент меню - _Build\Build Solution_.
    * Или используйте сочетание клавиш - _Ctrl+Shift+B_.
1. Откройте список ошибкок во вкладке [Error List](https://docs.microsoft.com/ru-ru/visualstudio/ide/find-and-fix-code-errors#review-the-error-list).
    * Выберите элемент меню - _View\Error List_.
    * Или используйте сочетание клавиш - _Ctrl+W, E_.
1. Используйте двойной щелчок мыши на тексте предупреждения компилятора во вкладке Error List. Visual Studio откроет файл [HelloWorld.cs](HelloWorldStyle/HelloWorld.cs) в окне редактирования.
1. Снова откройте вкладку Error List, используйте одинарный щелчок мыши на ссылке в поле "Code" любого элемента списка в поле. Visual Studio откроет страницу документации для выбранного предупреждения.
1. Откройте файл [HelloWorld.cs](HelloWorldStyle/HelloWorld.cs) и отформатируйте код в окне редактора.
    * Используйте сочетание клавиш - _Ctrl+K, Ctrl+D_.
1. Соберите решение, откройте вкладку Error List и сравните список предупреждений компилятора с списком, который был до этого.
1. Исправьте все предупреждения компилятора в файле [HelloWorld.cs](HelloWorldStyle/HelloWorld.cs).


## Исправьте ошибки компилятора

Для всех проектов решения включены дополнительные проверки на стилистические ошибки и добавлены анализаторы кода, чтобы помочь Вам поддерживать целостность кодовой базы и избежать наивных ошибок. Все ошибки и предупреждения компилятора C# доступны в окне Visual Studio [Error List](https://docs.microsoft.com/ru-ru/visualstudio/ide/find-and-fix-code-errors#review-the-error-list).

Если сообщение об ошибке или предупреждение компилятора поставило Вас в тупик, [откройте страницу документации ошибки или предупреждения](https://docs.microsoft.com/ru-ru/visualstudio/ide/find-and-fix-code-errors#review-errors-in-detail) или загуглите код ошибки в поисковике.

Также вы можете использовать [базу знаний правил Sonar](https://rules.sonarsource.com/csharp) для поиска дополнительной информации об ошибках, которые возникают на этапе проверки задания анализатором Sonar.


## Сохраните изменения

* [Пересоберите решение](https://docs.microsoft.com/ru-ru/visualstudio/ide/building-and-cleaning-projects-and-solutions-in-visual-studio) в Visual Studio.
* Откройте [окно Error List](https://docs.microsoft.com/ru-ru/visualstudio/ide/reference/error-list-window) и проверьте, что в окне нет ошибок и предупреждений компилятора. Если в окне есть ошибки или предупреждения, **исправьте их** и снова пересоберите решение.
* [Запустите юнит-тесты при помощи Test Explorer](https://docs.microsoft.com/ru-ru/visualstudio/test/run-unit-tests-with-test-explorer). Убедитесь, что все юнит тесты завершаются успешно. [Сделайте все юнит-тесты зелеными](https://stackoverflow.com/questions/276813/what-is-red-green-testing).
* Обязятельно просмотрите все ваши изменения **перед тем** как сохранить Ваши изменения.
    * Откройте вкладку "Changes" в окне [Team Explorer](https://docs.microsoft.com/ru-ru/visualstudio/ide/reference/team-explorer-reference).
    * Правой клавишей мыши нажмите на измененном файле.
    * Нажмите на пункте меню "Compare with Unmodified" чтобы открыть окно сравнения.
* [Зафиксируйте изменения](https://docs.microsoft.com/ru-ru/azure/devops/repos/git/commits#stage-your-changes) и [создайте коммит](https://docs.microsoft.com/ru-ru/azure/devops/repos/git/commits#create-a-commit).
* [Отправьте изменения во внешний репозиторий](https://docs.microsoft.com/ru-ru/azure/devops/repos/git/pushing).


## Дополнительная информация

* Visual Studio
  * [Getting Started with Visual Studio 2019](https://www.youtube.com/watch?v=1CgsMtUmVgs)
  * [Git Fundamentals](https://www.youtube.com/watch?v=c3482qAzZLQ)
  * [Default keyboard shortcuts in Visual Studio](https://docs.microsoft.com/en-us/visualstudio/ide/default-keyboard-shortcuts-in-visual-studio)
