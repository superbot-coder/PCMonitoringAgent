## **PC Monitoring Agent**

**[RUS] Это REAT API сервер, который транслирует показания сенсоров компьютера таких как температура, скорость вентиляторов, напряжение и т.д.  из программ AIDA64 и "Open Hardware Monitor" в JSON формат через http**

**[ENG] This is a REAT API server that broadcasts computer sensor readings such as temperature, fan speed, voltage, etc. from AIDA64 programs and "Open Hardware Monitor" to JSON format via HTTP**

**[rus] Список поддерживаемых запросов; [eng] List of supported queries:**
 - http://host:port/version
 - http://host:port/cpu_info
 - http://host:port/ohm_sensors
 - http://host:port/aida64_sensors
 - http://host:port/aida64_sensors_upper
 

#### **Настройка AIDA64 для экспорта данных сенсоров**

Необходимо открыть меню настройки, выбрать пункт "Внешние приложения" и в правой части окна установить галочку в "чекбоксе" с названием "Разрешить запись показаний датчиков в реестр"

![Screenshot](https://github.com/superbot-coder/PCMonitoringAgent/blob/main/images/image01.png "")

#### **Настройка Open Hardware Monitor для экспорта данных сенсоров**
Необходимо открыть в главном меню программы "Options" и в установить галочку в пункте меню "Log Sensors"
Так же можно сделать дополнительные настройки для автозапуска программы. Для этого необходимо установить галочки в пунктах меню:
- Starе Minimized
- Minimiz to Ttray
- Minimiz on Close
- Run On Windows Startup
Смотрите скриншот

![Screenshot](https://github.com/superbot-coder/PCMonitoringAgent/blob/main/images/image02.png "")

#### **Другие скриншоты**

![Screenshot](https://github.com/superbot-coder/PCMonitoringAgent/blob/main/images/Image_01.png "")
![Screenshot](https://github.com/superbot-coder/PCMonitoringAgent/blob/main/images/Image_02.png "")
![Screenshot](https://github.com/superbot-coder/PCMonitoringAgent/blob/main/images/Image_03.png "")
![Screenshot](https://github.com/superbot-coder/PCMonitoringAgent/blob/main/images/Image_04.png "")
![Screenshot](https://github.com/superbot-coder/PCMonitoringAgent/blob/main/images/image_05.png "")



