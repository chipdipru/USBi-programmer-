# USBi-programmer
С форума DIY Audio http://www.diyaudio.com/forums/digital-line-level/269111-low-cost-usbi-programmer-using-cypress-cy7c68013a-board-post4777018.html можно скачать текстовый файл с прошивкой, которая маскирует cy7c68013a под USBi.
это текстовый файл и его необходимо преобразовать в bin.
для этого скачайте из репозитария утилиту txt2bin.exe поместите её и текстовый файл в одну папку и запустите. Появится сконвертированный файл  24aa256.bin
С помощью USB программатор FLASH и EEPROM памяти - https://www.chipdip.ru/product/rdc2-0026a залейте этот файл в епромку на плате с cy7c68013a.
Есть два способа:
1.	Выпаять микросхему памяти и прошить её на программаторе. 
2.	Прошить не выпаивая подключившись к ней по I2C.
