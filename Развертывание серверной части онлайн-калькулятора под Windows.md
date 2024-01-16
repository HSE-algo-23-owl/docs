# Развертывание серверной части онлайн-калькулятора под Windows

**1. Клонирование репозитория** 
Копируем ссылку на https://github.com/HSE-algo-23-owl/algoscalc-back/tree/issue-15

![Ссылка на репозиторий](https://github.com/HSE-algo-23-owl/docs/tree/main/images/srv1.png)

Склонировать репозиторий в папку с проектом в терминале PyCharm

![Терминал PyCharm](images/srv11.png)


**2. Установка виртуального окружения для репозитория**
В Pycharm установить для репозитория виртуальное окружение - 
Settings -> Project -> Python interpreter -> Add interpreter -> Add local interpreter -> Virtualenv Environment -> New.

![Виртуальное окружение проекта algoscalc-back](images/srv2.png)

**3. Установка зависимостей из файла src/requirements.txt**
Установить в виртуальное окружение проекта зависимости из файла src/requirements.txt - в терминале выполнить pip install -r src/requirements.txt

**При установке зависимостей в терминале возникает ошибка**

 ![Виртуальное окружение проекта algoscalc-back](images/srv22.png)

 В папке src находим файл requirements.txt

 ![Файл requirements.txt](images/srv3.png)

 Копируем ссылку на проект, переходим в терминал cmd или Windows PowerShell, выполняем команду pip install -r src/requirements.txt

  ![Установка зависимостей через PowerShell](images/srv31.png)


