EN:
How to use ASA Failover state sensor
=============================================
1. Unpack ZIP archive with exe and ovl files
2. Copy file asafailoverstatus.exe to \PRTG Network Monitor\Custom Sensors\EXEXML folder
3. Copy files failoverstatus.ovl and asacpu.ovl to \PRTG Network Monitor\lookups\custom folder
4. Go to PRTG->Setup->System Administration->Administrative Tools for the Core Server
    and click Load Lookups and File Lists
5. In devices settings add credentials for Linux/Solaris/Mac OS. Credentials can be local or Radius
6. Add EXE/Script Advanced sensor, in dropdown list, select asafailoverstatus.exe
7. Parameners must be: -u %linuxuser -p %linuxpassword -i %host
8. If You want CPU utilization channel, add -c true parameter
PS:
PRTG Network Monitor folder, typicaly locate at: C:\Program Files (x86)

RUS:
Как использовать ASA Failover сенсор
=============================================
1. Распакуйте ZIP архив с exe и ovl файлами
2. Скопируйте файл asafailoverstatus.exe в директорию \PRTG Network Monitor\Custom Sensors\EXEXML
3. Скопируйте файлы files failoverstatus.ovl и asacpu.ovl в директорию \PRTG Network Monitor\lookups\custom
4. Зайдите в меню PRTG->Setup->System Administration->Administrative Tools for the Core Server
   и нажмите кнопку Load Lookups and File Lists
5. В настройкух устройства добавте учетую запись Linux/Solaris/Mac OS. Credentials (может быть как локадьная так и RADIUS)
6. Добавьте EXE/Script Advanced sensor, в выпадающем списке выберите asafailoverstatus.exe
7. Параметры дожны быть: -u %linuxuser -p %linuxpassword -i %host
8. Если вы хотите добавить канал CPU utilization, добавте параметр -c true

PS:
папка PRTG Network Monitor, обычно расположена по пути: C:\Program Files (x86)
