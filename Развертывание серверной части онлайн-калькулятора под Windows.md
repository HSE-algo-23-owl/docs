# Развертывание серверной части онлайн-калькулятора под Windows

**1. Клонирование репозитория** 
Копируем ссылку на https://github.com/HSE-algo-23-owl/algoscalc-back/tree/issue-15

![Ссылка на репозиторий](https://github.com/HSE-algo-23-owl/docs/blob/main/images/srv1.PNG)

Клонируем репозиторий в папку с проектом в терминале PyCharm

![Терминал PyCharm](https://github.com/HSE-algo-23-owl/docs/blob/main/images/srv11.PNG)


**2. Установка виртуального окружения для репозитория**
В Pycharm для репозитория устанавливаем виртуальное окружение - 
Settings -> Project -> Python interpreter -> Add interpreter -> Add local interpreter -> Virtualenv Environment -> New.

![Виртуальное окружение проекта algoscalc-back](https://github.com/HSE-algo-23-owl/docs/blob/main/images/srv2.PNG)

**3. Установка зависимостей из файла src/requirements.txt**
Устанавливаем в виртуальное окружение проекта зависимости из файла src/requirements.txt - в терминале выполняем pip install -r src/requirements.txt

**При установке зависимостей в терминале возникает ошибка**

 ![Виртуальное окружение проекта algoscalc-back](https://github.com/HSE-algo-23-owl/docs/blob/main/images/srv22.PNG)

 В папке src находим файл requirements.txt

 ![Файл requirements.txt](https://github.com/HSE-algo-23-owl/docs/blob/main/images/srv3.PNG)

 Копируем ссылку на проект, переходим в терминал cmd или Windows PowerShell, выполняем команду pip install -r src/requirements.txt

  ![Установка зависимостей через PowerShell](https://github.com/HSE-algo-23-owl/docs/blob/main/images/srw31.PNG)


