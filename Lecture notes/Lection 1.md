# Задачи администрирования информационных систем

## Функции и состав служб администратора системы

**Администратор системы** - это человек или группа людей, которые создают и затем эксплуатруют информационную систему мероприятия.

Функции:

1) установка и сопровождение компьютерных сетевых и информационных сетей
2) определение и согласование с фирмами-поставщиками всей аппаратно-программной и организационной части по реализации системы
3) планирование развития информационных систем и внедрения сервисов
4) решение вопросов ведения проектов
5) обучение технического персонала и пользователей
6) консультирование по компьютерным проблемам персонала предприятия и технических служб
7) решение проблем сбора статистики, мониторинга, диагностики, восстановления и сохранения системы, а также всех вопросов организации, соответствующих программных и аппаратных продуктов для этой деятельности
8) разработка программных продуктов на языках управления заданиями (например, скриптах) с целью создания технологии работы компании и синхронизации работы компонентов информационной системы
9) определение ошибок в работе прикладных, системных и аппаратных средств, используемых предприятием, и решение вопросов по их устранению

В настоящее время эти функции, как правило, выполняются совокупностью информационных служб предприятия:

- службами управления:

    1) конфигурацией - занимаются вопросами задания параметров запуска операционных систем и СУБД, заданием параметров запуска приложений

    2) контролем характеристик и ошибочными ситуациями - осуществляют мониторинг и сбор статистики параметров информационной системы с помощью специальных программно-аппаратных комплексов, устанавливают критерии определения опасных и тревожных ситуаций, следят за их обнаружением и устранением, используют специальные методы и средства диагностики ошибок

    3) безопасностью - противодействуют различным угрозам несанкционированного доступа, настраивают работу различных ОС, СУБД. Эти службы управляют всеми имеющимися в организации компьютерными средствами защиты

    4) производительностью - работают в тесном взаимодействии со службами управления по контролю характеристик и ошибочными ситуациями. При помощи аппаратно-программных комплексов они анализируют работу информационной системы и следят за временем работы приложения, временем отклика приложения, времем обращения к дисковой подсистеме ввода-вывода, задержкой передачи данных и др. Анализируя результаты совместно с другими службами, они определяют причины изменения параметров работы системы и способы предотвращения или коррекции ухудшений значений параметров

- службами планирования и развития - определяют техническую и экономическую эффективность от внедрения различного вида информационных услуг или сервисов компании, следят за появлением новых компьютерных технологий и оценивают целесообразность их использования, ведут внедряемые проекты и планируют работы других служб и компаний-поставщиков и инсталляторов по их реализации. Контролируют выполнение подрядными организациями работ по внедрению частей информационной системы или их модернизации

- службами эксплуатации и сопровождения - осуществляют архивирование (копирование) и восстановление информационной системы. Ведут базу данных копий при помощи программно-аппаратных средств, проводят проверки целостности данных средствами информационной системы, определяют стратегию восстановления информационной системы. Они же занимаются сопровождением аппаратных средств (например, заменой картриджа принтера), подключением новых
пользователей (например, организацией для них рабочего места), организацией электропитания, выполнением профилактических работ

- службами общего управления - занимаются управлением работы всех информационных служб, согласованием их действий, выработкой корпоративных стандартов (например, на формат документов), разработкой инструкций для пользователей, их обучением и консультацией, введением нормативно справочной документации необходимой в организации

## Общие понятия об открытых гетерогенных системах

**Корпоративная ИС** - информационная система, виртуально объединяющая все части одной организации, которые могут находиться в разных городах, частях страны или земного шара. Доступ пользователей в корпоративную систему возможен только для членов компании, ее клиентов или ее контрагентов.

**Глобальные ИС** - множество информационных систем, пересекающих национальные, коммерческие и континентальные границы для обеспечения глобального взаимодействия большого числа организаций и физических лиц. К глобальной системе имеет доступ любой пользователь в соответствии с определенными правилами, выработанными самоорганизованным комитетом пользователей и разработчиков такой системы.

**Открытая система** - любая система (компьютер, вычислительная сеть, операционная система, программный продукт), которая построена в соответствии с открытыми спецификациями для интерфейсов, служб и форматов.

**Спецификация** - формализованное описание аппаратных или программных компонентов, способов их функционирования, взаимодействия с другими компонентами, условий эксплуатации, ограничений и особых характеристик.

**Открытые спецификации** - опубликованные, общедоступные спецификации стандартизирующих организаций или компаний-разработчиков аппаратных и программных средств.

**Преимущества открытой системы**:

- возможность построения системы из аппаратных и программных средств различных производителей, придерживающихся одного и того же стандарта

- перенос созданного программного обеспечения с минимальными изменениями в широком диапазоне систем, полученных от одного или нескольких поставщиков

- возможность безболезненной замены отдельных компонентов системы другими, более совершенными, что позволяет ей развиваться с минимальными затратами

- возможность легкого сопряжения с другими информационными системами

- простоту освоения, обслуживания и введения нового персонала для поддержки системы

**Гетерогенная система** - система, использующая для распространения информации разные компьютеры разных производителей, различные интерфейсы и средства передачи данных, различное программное обеспечение и различную архитектуру ЭВМ. Без стандартизации работоспособность таких систем невозможна.

## Стандарты работы ИС и стандартизирующие организации

**Стандарт** — это вариант реализации протокола в аппаратуре или программном обеспечении, который отражается в документе, согласованном и принятом аккредитованной организацией, разрабатывающей стандарты. Стандарт содержит правила, руководства или характеристики для работ или их результатов в целях достижения оптимальной степени упорядочения и согласованности в заданном контексте.

**Виды стандартов**:

1) Юридические - подтверждаются законами, которые приняты государством
2) Фактические стандарты - их использование не определено законами или нормативами
3) Корпоративные стандарты - разрабатываются и внедряются частными коммерческими компаниями для своих продуктов
4) Стандарты стандартизирующих организаций создаются специализированными организациями или самоорганизующимися комитетами и форумами (ITU, ISO, IEEE, EIA, TIA)

## Объекты администрирования и модели управления

### Объекты администрирования в информационных системах

**Задачи администрирования подсистем**:

1) администрирование кабельной системы
2) поддержка и сопровождение аппаратной части
3) администрирование сетевой системы
4) администрирование прикладной системы
5) администрирование операционной системы
6) Web-администрирование
7) управление информационными службами
8) администрирование СУБД

В процессе администрирования ИС администратор системы должен руководствоваться **моделью администрирования** - набором функций по управлению подсистемой или информационным процессом.

Функции (модели) по управлению техническим обеспечением, организационной и функциональной подсистемами:

1) ISO OSI
2) ISO FCAPS
3) OGC ITIL
4) ITU TMN
5) TMF eTOM

### Модель сетевого управления ISO OSI

>- Модель сетевого управления ISO OSI Management Framework - развитие общей семиуровневой модели взаимодействия открытых систем для случая, когда одна система управляет другой
>
>- Стандарты ISO в области управления используют специальную терминологию, которой в свою очередь воспользовались создатели Internet в протоколе SNMP (Simple Network Management Protocol - простой протокол управления сетью)
>
>- Обмен управляющей информацией с помощью протокола управления (Management Protocol) происходит между субъектами приложений управления системами (SMAE)
>
>- Cубъект в модели OSI - активный в данный момент процесс (протокол) какого-либо уровня, участвующий во взаимодействии
>
>- Примерами SMAE являются агенты и менеджеры систем управления ИС
>
>- Уведомления (notifications) - сообщения, которые агент посылает менеджеру по своей инициативе

**Вспомогательные службы общего назначения** прикладного уровеня модели OSI, которые используются прикладными протоколами и пользовательскими приложениями для автоматизации наиболее часто выполняемых действий:

1) ACSE (Association Control Service Element). Эта служба отвечает за установление соединений между приложениями различных систем. Соединение (сессия, сеанс) на прикладном уровне OSI носит название ассоциации. Ассоциации бывают индивидуальными и групповыми (shared)

2) RTSE (Reliable Transfer Service Element). Служба осуществляет поддержку восстановления диалога, вызванного разрывом нижележащих коммуникационных служб, в рамках ассоциации

3) ROSE (Remote Operations Service Element). Организует выполнение программных функций на удаленных машинах. Является аналогом службы RPC (Remote Procedure Call >- вызов удаленных процедур)

Основная модель управления OSI включает:

1) управление системами - имеет дело с управляемыми объектами на всех семи уровнях OSI, включая прикладной уровень. Оно основано на надежной передаче с установлением соединения управляющей информации между конечными системами. Необходимо подчеркнуть, что модель управления OSI не разрешает использовать службы без установления соединения

2) управление N-уровнем - ограничено управляемыми объектами какого-то определенного уровня семиуровневой модели. Протокол управления использует при этом коммуникационные протоколы нижележащих уровней. Управление N-уровнем полезно, когда нет возможности использовать все семь уровней OSI. В этом случае допускается пользоваться протоколом управления N-уровня, который строго предназначен для данного уровня

3) операции N-уровня - мониторинг и управлениt на основе управляющей информации, содержащейся в коммуникационных протоколах только данного уровня. Например, данные мониторинга сети, содержащиеся во фреймах
STM-n, технологии SDH, относятся к операциям N-уровня, а именно физического уровня. Стандарты на управление N-уровнем и операции N-уровня не входят в набор протоколов управления OSI

Это разбиение на три области сделано для того, чтобы учесть всё возможные ситуации, возникающие при управлении

### Модель управления ITU TMN

>- Архитектура и принципы построения TMN обеспечивают реализацию задач по управлению, оперативному контролю и эксплуатации разнородного телекоммуникационного оборудования и систем электросвязи, которые изготовлены различными фирмами -производителями

TMN предназначена для:

1) Управления услугами сетей связи
2) Эксплуатации и технического обслуживания оборудования
3) Оперативно-технического контроля и администрирования сетевых устройств с целью обеспечить нормативное качество оказания услуг связи

>- Объектами управления TMN являются **телекоммуникационные ресурсы** - реальное оборудование связи (стойки, функциональные блоки, модули, на определенные свойства которых можно осуществлять целенаправленное управляющее воздействие)
>
>- Обмен командами управления и иной информацией между ТMN и оборудованием связи осуществляется через опорные точки, которые реализуются в виде стандартизованных или нестандартизованных интерфейсов TMN

Функции прикладного уровня TMN реализуются с помощью одной или нескольких операционных систем (Operations Systems). Операционные системы выполняют следующие задачи:

1) Обеспечивают обработку данных (поступающих от управляемой сети электросвязи) в целях мониторинга и контроля функционирования телекоммуникационного оборудования, а также для обеспечения работы собственно TMN
2) Поддерживают информационную модель сети электросвязи, которая представляет собой описание физических объектов электросвязи с использованием принятой информационной технологии и специальных программных средств, например, СУБД
3) Обеспечивают работу прикладных программных средств управления (приложение управления), которые реализуют большинство услуг и функций управления системами

С учетом характеристик управления открытыми системами TMN функционально должна обеспечивать:

1) Обмен информацией управления между сетями электросвязи и сетью TMN
2) Преобразование информации управления для различных систем связи в единый формат в целях обеспечения совместимости и согласованности данных в TMN
3) Перенос информации управления между различными компонентами в TMN
4) Анализ и соответствующую реакцию на информацию управления
5) Преобразование информации управления в форму, которая понятна пользователю системы управления — оператору или администратору; в результате повышается качество услуг управления и обеспечивается дружественное взаимодействие с пользователями посредством общепринятых стандартов графического отображения информации;
6) Защищенный доступ к информации по управлению для пользователей TMN
7) Контроль крупных и сложных объектов управления

Цели внедрения TMN:

1) Минимальное время реакции системы управления на существенные сетевые события
2) Минимизация нагрузки, создаваемой системой управления; это особенно важно в случае, когда для передачи информации управления используются ресурсы сети электросвязи общего пользования, а не выделенные каналы связи
3) Реализация процедур для изоляции мест повреждения (неисправностей) в реальном времени, возможность дистанционного вызова и запуска процедур восстановления повреждений
4) Учет различных схем организации сетей связи при реализации функций управления

Уровни управления TMN:

1) уровень управления бизнесом (Business Management Layer — BML)
2) уровень управления услугами (Service Management Layer — SML)
3) уровень управления сетью (Network Management Layer — NML)
4) уровень управления элементом (Element Management Layer — EML)
5) уровень элемента сети (Network Element Layer — NEL)

### Модель управления ISO FCAPS

>- FCAPS (Fault Configuration Account Performance Security) – модель Международной организации по стандартизации, в которой отражены ключевые функции администрирования и управления сетями (обеспечивающей подсистемы ИС)
и не рассматриваются вопросы администрирования функциональной или организационной подсистем

Согласно модели FCAPS, все аспекты администрирования сети ИС можно описать при помощи пяти видов функций:

1) (F) Fault Management (управление отказами) - обнаружение отказов в устройствах сети, сопоставление аварийной информации от различных устройств, локализация отказов и инициирование корректирующих действий

2) (С) Configuration Management (управление конфигурированием) - возможность отслеживания изменений, конфигурирования, передачи и установки программного обеспечения на всех устройствах сети

3) (A) Accounting Management (управление учетом) - возможность сбора и передачи учетной информации для генерации отчетов об использовании сетевых ресурсов

4) (Р) Performance Management (управление производительностью) - непрерывный источник информации для мониторинга показателей работы сети (QoS (Quality of Service, Качество обслуживания), ToS (Terms of Service, Тип обслуживания)) и распределения сетевых ресурсов

5) (S) Security Management (Управление безопасностью) - возможность управления доступом к сетевым ресурсам и защитой от угроз
