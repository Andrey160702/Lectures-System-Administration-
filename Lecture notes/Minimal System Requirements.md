# Минимальные системные требования ОС

Каждая ОС имеет минимальные требования к оборудованию, на котором она может работать. Это достаточные ресурсы для функционирования самой ОС и утилит её обслуживания. Но для запуска прикладного ПО может потребоваться большее количество ресурсов. Как правило именно используемое ПО определяет оборудование, которое будет закупаться и использоваться для установки ОС.

Минимальные системные требования для Windows 7:

- 32-разрядный (x86) или 64-разрядный (x64) процессор с тактовой частотой 1 ГГц или выше
- 1 ГБ (для 32-разрядного процессора) или 2 ГБ (для 64-разрядного процессора) ОЗУ
- 16 ГБ (для 32-разрядной системы) или 20 ГБ (для 64-разрядной системы) свободного места на жестком диске
- Графическое устройство DirectX 9 с драйвером WDDM 1.0 или более поздней версии

Минимальные системные требования для Windows 8.1:

- 32-разрядный (x86) или 64-разрядный (x64) процессор с тактовой частотой 1 ГГц или выше
- 1 ГБ (для 32-разрядного процессора) или 2 ГБ (для 64-разрядного процессора) ОЗУ
- 16 ГБ (для 32-разрядной системы) или 20 ГБ (для 64-разрядной системы) свободного места на жестком диске
- Графическое устройство DirectX 9 с драйвером WDDM 1.0 или более поздней версии

Минимальные системные требования для Windows 10:

- 32-разрядный (x86) или 64-разрядный (x64) процессор с тактовой частотой 1 ГГц или выше
- 1 ГБ (для 32-разрядного процессора) или 2 ГБ (для 64-разрядного процессора) ОЗУ
- 16 ГБ (для 32-разрядной системы) или 20 ГБ (для 64-разрядной системы) свободного места на жестком диске
- Графическое устройство DirectX 9 с драйвером WDDM 1.0 или более поздней версии

Как видим, для этих трех систем минимальные системные требования - одинаковы. Стоит заметить, что соответствие этим требованиям **позволит функционировать** операционным системам на устройстве. В реальности того же места на диске понаобится больше - часть расходуется на файл подкачки и сна, часть для скачивания и установки обновлений. Журналы, которые по умолчанию ведёт настольная версия Windows не занимают много места и регулярно очищаются.

Минимальные системные требования для Windows Server 2012:

- Процессор 64-х разрядный с частотой 1.4 ГГц
- ОЗУ минимум  512 Мб
- Место на устройстве хранения 32 GB
- Видеокарта и монитор с разрешением не менее 800х600
- Клавиатура и мышь
- Доступ к сети Интернет

Требования к конкретным драйверам на видеокарте, как у настольных версий - здесь нет. Доступ к сети Интернет не является необходимым для установки, но без него будет осложнена работа с обновлениями. Для сервера обновления безопасности являются критичными и поэтому доступ к сети выносится отдельным пунктом

Минимальные системные требования для Windows Server 2016:

- Процессор 64-х разрядный с частотой 1.4 ГГц
- ОЗУ минимум  512 Мб
- Место на устройстве хранения 32 GB
- Видеокарта и монитор с разрешением не менее 800х600
- Клавиатура и мышь
- Доступ к сети Интернет

Системные требования вроде бы аналогичны Windows Server 2012, но тут добавляются требования поддержки процессором инструкций NX, DEP, CMPXCHG16b, LAHF/SAHF и PrefetchW. А так же второго уровня трансляции адресов с использованием EPT or NPT. Для памяти добавляется требование наличия коррекции ошибок (ECC)

Минимальные системные требования Debian 11:

- 1 ГБ оперативной памяти или 512 МБ без установки настольных приложений
- 2 ГБ свободного дискового пространства или 10 ГБ с инсталляцией дополнительного программного обеспечения
- Ограничений по используемым процессорам не имеется
Поддерживаемые архитектуры:

  - x86-64 с поддержкой запуска 32-х разрядных приложений
  - ARMv8-A
  - armel (набор инструкций ARMv4T с порядком от младшего к старшему)
  - armhf (набор инструкций ARMv7 с требованием аппаратного FPU)
  - х86
  - mips (с порядком от старшего к младшему)
  - mipsel: (с порядком от младшего к старшему)
  - mips64el (64-х разрядная архитектура с порядком от младшего к старшему)
  - ppc64el (PowerPC с порядком от младшего к старшему для процессоров POWER7+ и POWER8)
  - s390x: (z/Architecture с 64-х разрядным пользовательским окружением))
- Видеокарта с поддержкой соответствующего драйвера (в случае работы в консольном интерфейсе можно вообще обойтись без неё)

Стоит отметить, что перечислены не все поддериваемые архитектуры процессоров. В плане поддержки архитектур Debian является своеобразным рекордсменом среди дистрибутивов Linux
