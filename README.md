# **PC Monitoring Agent**

**[RUS] Это REST API сервер, который транслирует показания сенсоров компьютера таких как температура, скорость вентиляторов, напряжение и т.д.  из программ AIDA64 и "Open Hardware Monitor" в JSON формат через HTTP**

**[ENG] This is a REST API server that broadcasts computer sensor readings such as temperature, fan speed, voltage, etc. from AIDA64 programs and "Open Hardware Monitor" to JSON format via HTTP**

**[rus] Список поддерживаемых запросов; [eng] List of supported queries:**
- host:port/access_key
- host:port/aida64_sensors
- host:port/aida64_sensors.json
- host:port/cpu_info
- host:port/cpu_info.json 
- host:port/ohm_sensors
- host:port/ohm_sensors.json
- host:port/reboot
- host:port/shellexecute
- host:port/shutdown
- host:port/test_authorization
- host:port/update_agent
- host:port/version
 
### **Настройка AIDA64 для экспорта данных сенсоров**

Необходимо открыть меню настройки, выбрать пункт "Внешние приложения" и в правой части окна установить галочку в "чекбоксе" с названием "Разрешить запись показаний датчиков в реестр"

![Screenshot](https://github.com/superbot-coder/PCMonitoringAgent/blob/main/images/image01.png "")

### **Настройка Open Hardware Monitor для экспорта данных сенсоров**
Необходимо открыть в главном меню программы "Options" и в установить галочку в пункте меню "Log Sensors"
Так же можно сделать дополнительные настройки для автозапуска программы. Для этого необходимо установить галочки в пунктах меню:
- Starе Minimized
- Minimiz to Ttray
- Minimiz on Close
- Run On Windows Startup
Смотрите скриншот

![Screenshot](https://github.com/superbot-coder/PCMonitoringAgent/blob/main/images/image02.png "")

### **Другие скриншоты**

![Screenshot](https://github.com/superbot-coder/PCMonitoringAgent/blob/main/images/Image_01.png "")
![Screenshot](https://github.com/superbot-coder/PCMonitoringAgent/blob/main/images/Image_02.png "")
![Screenshot](https://github.com/superbot-coder/PCMonitoringAgent/blob/main/images/Image_03.png "")
![Screenshot](https://github.com/superbot-coder/PCMonitoringAgent/blob/main/images/Image_04.png "")
![Screenshot](https://github.com/superbot-coder/PCMonitoringAgent/blob/main/images/image_05.png "")



