## Joomla CMS

### Запуск в docker

Запускаем Joomla: `docker compose -f joomla.docker-compose.yml up -d`

Переходим на [localhost:80](http://localhost:80):

1. Создаем учетную запись `admin/admin`

   ![step1.png](images/joomla/step1.png)
2. Подключаемся к MySQL базе данных с паролем `joomla_pass`

   ![step2.png](images/joomla/step2.png)
3. Устанавливаем

   ![step3.png](images/joomla/step3.png)
4. Удаляем директорию и переходим в панель управления под `admin/admin`

   ![step4.png](images/joomla/step4.png)

### Установка нашего плагина

В панели управления:

1. Идем в установки расширений

   ![step5.png](images/joomla/step5.png)
2. Устанавливаем наш плагин по ссылке

   ![step6.png](images/joomla/step6.png)
3. Плагин успешно установлен

   ![step7.png](images/joomla/step7.png)
4. Включаем наш плагин

   ![step8.png](images/joomla/step8.png)
5. Плагин включен

   ![step9.png](images/joomla/step9.png)
