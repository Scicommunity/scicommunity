---
title: TOGAF. История создания
weight: 1
bookToc: true
bookCollapseSection: false
aliases:
  - История TOGAF
---

# История создания стандарта TOGAF

## Введение

Стандарт TOGAF (The Open Group Architecture Framework) является сегодня одной из наиболее распространённых методологий корпоративной архитектуры. 
Объективным показателем лидерства TOGAF является количество сертификаций профессионалов, по которым имеются проверяемые данные:
| Год  | TOGAF Сертификации | Источник       |
| ---- | ------------------ | -------------- |
| 2011 | ~15,000            | Wikipedia      |
| 2017 | 70,131             | ITSM.tools     |
| 2018 | 77,500+            | Wikipedia      |
| 2025 | 150,000+           | OpenGroup Blog |

Однако история его создания началась значительно ранее, чем в 2011 году, с фундаментальных работ американского военного ведомства и разработки ведущих IT-консалтинговых компаний.

## Предыстория: корни в методологиях 1960-1980-х годов

### Business Systems Planning (BSP) и начало планирования архитектуры

Истоки TOGAF уходят корнями в методологию **Business Systems Planning** (BSP), разработанную компанией IBM в начале 1960-х годов, хотя формально она была представлена в 1981 году. BSP стала революционной методологией, впервые предложившей структурированный подход к планированию информационных систем, связывающий бизнес-стратегию организации с её IT-инвестициями.[^1]

BSP была ответом на признание того, что данные превратились в корпоративный актив, требующий планирования наряду с приложениями. Методология включала 15 этапов и охватывала жизненный цикл развития архитектуры — от понимания текущего состояния до разработки целевого состояния и плана миграции.

### PRISM Framework и формализация четырёх доменов (1986)

Важной вехой в истории архитектурного мышления стала публикация доклада **PRISM** в 1986 году, подготовленного консорциумом при участии IBM и других организаций. PRISM впервые систематически разделил архитектуру организации на **четыре основных домена**:[^2]

- **Бизнес-архитектура** — организационные структуры, процессы и функции
- **Архитектура данных** — информационные активы и управление данными
- **Архитектура приложений** — информационные системы и их взаимодействие
- **Архитектура технологии** — инфраструктура, оборудование и платформы

Эта четырёхдоменная классификация оказалась чрезвычайно жизнеспособной и затем была унаследована практически всеми крупными фреймворками корпоративной архитектуры, включая TOGAF.[^3][^2]

### Zachman Framework (1987)

В 1987 году Джон Захман опубликовал статью в IBM Systems Journal, представив **Zachman Framework**, считающийся первым формальным фреймворком корпоративной архитектуры. Zachman предложил иную организацию архитектурного описания — матричную структуру с шестью перспективами (планировщик, владелец, проектировщик, строитель, подрядчик, функционирующее предприятие) и тремя исходными измерениями (что, как, где).[^4]

Хотя структура Zachman отличалась от PRISM, оба подхода влияли на последующие разработки, включая создание TAFIM.

## TAFIM: Фундамент для TOGAF

### Начало разработки (1986)

Разработка **Technical Architecture Framework for Information Management** (TAFIM) началась примерно в 1986 году в Агентстве оборонной информационной системы США (DISA) при Министерстве обороны. Проект был возглавлен командой, включавшей Burnes St. Patrick Hollyman, James M. Kerr и John Keane.[^5][^6]

### Развитие TAFIM (1986-1996)

Разработка TAFIM была вдохновлена первыми концепциями NIST Application Portability Profile и стандартом POSIX (IEEE P1003.00SE). Первый черновик был завершён в 1991 году. До официальной публикации в 1996 году подход был успешно апробирован в различных структурах Министерства обороны, включая Корпус морской пехоты США и Управление здравоохранения Минобороны.[^6]

### Структура TAFIM

TAFIM состояла из 7-8 томов, охватывающих различные аспекты архитектуры. Ключевые компоненты включали:

- **Том 1** — Обзор
- **Том 2** — Техническая модель ссылок (Technical Reference Model) — концептуальная модель информационных сервисов и их интерфейсов
- **Том 3** — Концепции архитектуры и рекомендации по дизайну
- **Том 4** — Руководство по планированию архитектуры на основе стандартов DoD
- **Том 6** — Целевая архитектура безопасности DoD
- **Том 7** — Принятые стандарты информационных технологий

TAFIM рекомендовала описывать четыре домена корпоративной архитектуры: **организационная работа, информация, приложения и технология**, и предусматривала семиэтапный итеративный процесс разработки архитектуры, включая документирование исходного и целевого состояний, анализ разрывов и планирование миграции.[^7]

## Создание TOGAF: 1994-2001

### Инициирование проекта (1994-1995)

В 1994 году The Open Group, международный консорциум, сосредоточенный на разработке открытых стандартов, сформулировал требования для создания универсального фреймворка корпоративной архитектуры. The Open Group получил явное разрешение и поддержку от Министерства обороны США на создание TOGAF на основе TAFIM, который был результатом многолетних усилий разработки и миллионов долларов инвестиций американского правительства.[^8]

### TOGAF 1.0 (1995)

**TOGAF версия 1.0** была представлена в 1995 году как "proof of concept". Первая версия была основана главным образом на TAFIM, но также включала идеи из **Integrated Architecture Framework** (IAF) компании Capgemini, которая развивалась Capgemini с начала 1990-х годов на основе опыта архитекторов в практических проектах для клиентов.[^9][^10]

Capgemini IAF (первая версия выпущена в 1996 году) состояла из четырёх доменов: бизнес-архитектура, информационная архитектура, информационные системы и инфраструктура технологии, и предоставляла четыре уровня абстракции: контекстный (Почему), концептуальный (Что), логический (Как) и физический (Чем).[^9]

### Быстрая эволюция ранних версий (1996-2000)

TOGAF развивался с впечатляющей скоростью в своих ранних версиях:


| Год | Версия | Ключевые достижения |
| :-- | :-- | :-- |
| 1996 | TOGAF 2 | Практическое применение (Proof of Application) |
| 1997 | TOGAF 3 | Значимость для практических архитектур, введение концепции Building Blocks |
| 1998 | TOGAF 4 | TOGAF в контексте — введение концепции Enterprise Continuum |
| 1999 | TOGAF 5 | Business Scenarios — метод для определения требований к архитектуре |
| 2000 | TOGAF 6 | Представления архитектуры; интеграция стандарта ANSI/IEEE 1471[^10] |

Каждая версия вносила вклад в превращение TOGAF из технического фреймворка для планирования информационной архитектуры в комплексный фреймворк корпоративной архитектуры.

## Введение Architecture Development Method (ADM): TOGAF 7

### TOGAF 7 — Technical Edition (2001)

**TOGAF версия 7** была опубликована в декабре 2001 года под названием "Technical Edition". Это была поворотная версия, в которой **Architecture Development Method (ADM)** был впервые формально интегрирован в состав фреймворка как его ядро.[^11][^10]

ADM предоставила открытый, основанный на консенсусе методологический подход к разработке корпоративной архитектуры. В TOGAF 7 ADM включала циклический процесс развития архитектуры, хотя ранние версии ещё сохраняли технический акцент.[^12]

### Основные нововведения TOGAF 7

По данным документов того времени, TOGAF 7 представила следующие ключевые нововведения:[^13][^12]

- **Интеграция ANSI/IEEE Std 1471-2000** — стандарт для описания архитектуры, включающий рекомендации по представлениям архитектуры
- **Architecture Compliance Reviews** — процедуры и чек-листы для обеспечения соответствия архитектуре в проектах разработки (на основе работ Boeing)
- **Architecture Patterns** — методология для использования архитектурных паттернов в отличие от паттернов проектирования (на основе работ IBM и US Treasury)
- **Architecture Principles** — расширенные примеры принципов архитектуры (на основе работ US Air Force)
- **Business Scenarios** — метод для определения ключевых бизнес-драйверов и требований к архитектуре
- **Model-Based Representations** — представления ADM и его результатов в модельной форме


## TOGAF 8: Трансформация в полноценный фреймворк корпоративной архитектуры

### TOGAF 8 — Enterprise Edition (2002)

**TOGAF версия 8** была выпущена в декабре 2002 года под названием "Enterprise Edition". Это была фундаментальная переработка, в результате которой TOGAF трансформировался из технического фреймворка в **полнофункциональный фреймворк корпоративной архитектуры**.[^14][^11]

Согласно документам того времени, TOGAF версии 8 интегрировал различные аспекты корпоративной архитектуры, и он официально стал полноценным фреймворком для Enterprise Architecture.[^15]

### Явное введение четырёх доменов в TOGAF 8

В TOGAF 8 четыре домена архитектуры были явно и структурировано интегрированы в ADM:

- **Фаза B: Business Architecture** — определение целей, стратегии, функций и процессов бизнеса
- **Фаза C: Information Systems Architectures** — разделена на две подфазы:
    - **Data Architecture** (архитектура данных)
    - **Application Architecture** (архитектура приложений)
- **Фаза D: Technology Architecture** — определение требуемой IT-инфраструктуры

TOGAF 8 явно признавал, что **Data Architecture и Application Architecture** вместе составляют **Information Systems Architecture**.[^15]

### TOGAF 8.1 и 8.1.1 (2003-2006)

Версия **TOGAF 8.1** была опубликована в декабре 2003 года, введя уточнения и дополнения. Версия **TOGAF 8.1.1** была выпущена в ноябре 2006 года, когда The Open Group официально зарегистрировала TOGAF как торговую марку.[^11]

К 2006 году TOGAF уже завоевал широкое признание в индустрии как практический, применимый фреймворк.

## Созревание фреймворка: TOGAF 9

### TOGAF 9 (2009)

**TOGAF версия 9.0** была выпущена 2 февраля 2009 года и представила **значительный скачок в зрелости фреймворка**. Это была первая версия, включившая формальную **Content Metamodel** (модель содержимого метаклассов) и **Architecture Content Framework** (фреймворк содержимого архитектуры).

### Введение Content Metamodel и формализация доменов

Content Metamodel в TOGAF 9 впервые предоставила **формальное, структурированное определение элементов, которые должны быть созданы в каждом домене архитектуры**. Для каждого домена были определены специфические артефакты:

#### Business Architecture (Фаза B)

- Organization/Actor Catalog
- Role Catalog
- Business Service/Function Catalog
- Process/Event/Control/Product Catalog
- Driver/Goal/Objective Catalog
- Business Interaction Matrix
- Business Footprint Diagram
- Process Flow Diagram


#### Data Architecture (Фаза C)

- **Data Entity/Data Component Catalog** — каталог сущностей данных
- **Data Entity/Business Function Matrix** — матрица связи сущностей данных и бизнес-функций
- **System/Data Matrix** — матрица связи систем и данных
- **Class Diagram** — диаграммы классов данных
- **Data Dissemination Diagram** — диаграмма распространения данных
- **Data Security Diagram** — диаграмма безопасности данных
- **Class Hierarchy Diagram** — диаграмма иерархии классов
- **Data Migration Diagram** — диаграмма миграции данных
- **Data Lifecycle Diagram** — диаграмма жизненного цикла данных


#### Application Architecture (Фаза C)

- Application Portfolio Catalog
- Interface Catalog
- System/Organization Matrix
- Application Interaction Matrix
- Application Communication Diagram


#### Technology Architecture (Фаза D)

- Technology Standards Catalog
- Technology Portfolio Catalog
- System/Technology Matrix
- Networked Computing/Hardware Diagram
- Communications Engineering Diagram


### Архитектурный репозиторий и Enterprise Continuum

TOGAF 9 также ввёл:

- **Architecture Repository** — формальный репозиторий для хранения архитектурных артефактов
- **Enterprise Continuum** — структурированный способ классификации архитектур и решений от обобщённых к специфическим
- **Formal Governance Model** — формальная модель управления архитектурой


### TOGAF 9.1 (2011)

**TOGAF версия 9.1** была выпущена в 2011 году, внеся дополнительные уточнения и расширенное руководство по применению фреймворка.[^16]

## Модернизация и актуализация: TOGAF 9.2 и 10

### TOGAF 9.2 (2018)

**TOGAF версия 9.2** была официально объявлена 16 апреля 2018 года. Это была первая значительная обновление со времён выпуска версии 9.1 в 2011 году.[^17]

Основные нововведения в TOGAF 9.2:[^17]

- Введение **TOGAF Library** — справочной библиотеки, содержащей рекомендации, шаблоны, паттерны и другие справочные материалы для ускорения создания новых архитектур
- **Повышенный акцент на business architecture** — добавлено десять новых руководств по enterprise architecture, относящихся к бизнес-архитектуре
- Переорганизация и очистка документации — сокращение объёма с 692 страниц в версии 9.1 до 532 страниц


### TOGAF 10 (2022)

**TOGAF версия 10** была выпущена 25 апреля 2022 года и представила существенное переструктурирование фреймворка.[^18][^16]

#### Ключевые изменения в TOGAF 10:

- **Модульная структура** — переход от единого монолитного документа к модульному формату с отдельными руководствами для различных тематических областей
- **Fundamental Content** — основное содержимое, состоящее из 6 взаимосвязанных документов, содержащих универсальные концепции
- **Series Guides** — специализированные руководства по темам, таким как Agile, безопасность, цифровая трансформация и другие
- **Управление несколькими состояниями архитектуры** — формализация различных состояний архитектуры (текущее, переходные, целевое)
- **Архитектурная абстракция на четырёх уровнях**:[^18]
    - **Contextual (Почему)** — контекстный уровень
    - **Conceptual (Что)** — концептуальный уровень
    - **Logical (Как)** — логический уровень
    - **Physical (Чем)** — физический уровень
- **Усиленный акцент на Agile** — интеграция методологий Agile и DevOps в фреймворк
- **Улучшенное управление архитектурой** — новые концепции управления целевыми состояниями и их реализацией


## Заключение

История создания TOGAF отражает эволюцию думки в области корпоративной архитектуры в течение нескольких десятилетий. От методологий планирования информационных систем IBM 1960-х годов через разработку TAFIM в американском Министерстве обороны к современному комплексному фреймворку — TOGAF прошёл путь постоянного развития и адаптации к меняющимся потребностям организаций.

Ключевые вехи этого пути:

- **1960-1980-е** — Становление архитектурного мышления (BSP, PRISM, Zachman)
- **1986-1996** — Разработка TAFIM как детального руководства для DoD
- **1995** — Создание TOGAF на основе TAFIM и опыта Capgemini IAF
- **1995-2001** — Быстрое развитие ранних версий TOGAF (1-7)
- **2001** — Введение Architecture Development Method в TOGAF 7
- **2002** — Трансформация в полнофункциональный фреймворк корпоративной архитектуры (TOGAF 8)
- **2009** — Введение формальной Content Metamodel и явное структурирование четырёх доменов (TOGAF 9)
- **2018** — Введение TOGAF Library и усиление акцента на бизнес-архитектуру (TOGAF 9.2)
- **2022** — Модульное переструктурирование и интеграция Agile (TOGAF 10)

Четырёхдоменная архитектура, впервые введённая в PRISM в 1986 году и затем включённая в TAFIM, была унаследована TOGAF и остаётся его центральным организующим принципом. Архитектура данных, в частности, эволюционировала от простого признания её важности в ранних версиях к явной и формально структурированной субсистеме архитектуры в TOGAF 9 с метаклассом содержимого, определяющим специфические артефакты, модели и диаграммы для управления данными на протяжении всего жизненного цикла организации.

***

**Основные источники:**

The Open Group Architecture Framework official documentation (versions 1.0-10.0)[^19]

Wikipedia: The Open Group Architecture Framework[^11]

The TOGAF® Standard — Introduction[^8]

TAFIM: Technical Architecture Framework for Information Management[^5][^6]

Integrated Architecture Framework (IAF) — Capgemini[^9]

TOGAF Version 7 presentations and documentation[^10][^12][^13]

TOGAF Version 8 documentation[^14][^15]

TOGAF Version 9 Content Framework documentation[^20][^16]

TOGAF Version 10 documentation[^21][^18]

Enterprise Architecture history and frameworks (BSP, PRISM, Zachman, EAP)[^4][^7][^2][^3][^1]

***

**Перечень основных и дополнительных ссылок:**
<span style="display:none">[^22][^23][^24][^25][^26][^27][^28][^29][^30][^31][^32][^33][^34][^35][^36][^37][^38][^39][^40][^41][^42][^43][^44][^45][^46][^47][^48][^49][^50][^51][^52][^53][^54][^55][^56][^57][^58][^59][^60][^61][^62][^63][^64][^65][^66][^67]</span>
<div align="center">⁂</div>

[^1]: https://www.academia.edu/36155270/Critical_Questions_in_Enterprise_Architecture_Research

[^2]: https://www.linkedin.com/pulse/brief-history-ea-graham-berrisford-znl0e

[^3]: http://grahamberrisford.com/01EAingeneral/EAinGeneral/Architecture Frameworks you might look at.htm

[^4]: http://rogersessions.com/images/PapersAndBooks/TopFourEAMethodologies.pdf

[^5]: https://en.wikipedia.org/wiki/TAFIM

[^6]: https://cio-wiki.org/wiki/Technical_Architecture_Framework_for_Information_Management_(TAFIM)

[^7]: https://www.kotusev.com/The History of Enterprise Architecture - An Evidence-Based Review.pdf

[^8]: http://www.togaf.org/chap01.html

[^9]: https://en.wikipedia.org/wiki/Integrated_Architecture_Framework

[^10]: https://www.opengroup.org/architecture/0207bos/presents/spencer.pdf

[^11]: https://en.wikipedia.org/wiki/The_Open_Group_Architecture_Framework

[^12]: https://www.opengroup.org/architecture/0201anah/briefing/togaf7.pdf

[^13]: https://www.opengroup.org/architecture/togaf7/presents/togaf_ovu.pdf

[^14]: http://www6.opengroup.org/togaf/index811.htm

[^15]: https://www.opengroup.org/architecture/0210can/togaf8/doc-review/togaf8cr/c/p1/enterprise.htm

[^16]: https://www.go-togaf.com/comprehensive-guide-to-the-evolution-of-togaf-from-inception-to-togaf-10/

[^17]: https://kotusev.com/TOGAF Version 9.2 - What's New.pdf

[^18]: https://www.detecon.com/wp-content/uploads/2025/10/The-TOGAF-Standard-10th-edition-course-Zurich-Switzerland-Whats-new.pdf

[^19]: https://guides.visual-paradigm.com/the-history-of-togaf-ea-framework/

[^20]: https://archive.opengroup.org/public/member/proceedings/q209/q209a/Presentations/turner.pdf

[^21]: https://www.avtechcn.com/pdf/togaf10part01.pdf

[^22]: https://www.knowledgehut.com/blog/it-service-management/togaf-phases

[^23]: https://kotusev.com/A Comparison of the Top Four Enterprise Architecture Frameworks.pdf

[^24]: https://www.bcs.org/articles-opinion-and-research/enterprise-architecture-frameworks-the-fad-of-the-century/

[^25]: https://university.sk/wp-content/uploads/2020/01/TOGAF_v9_2_specifikacia.pdf

[^26]: https://atdsolution.com/resource/togaf-10-architecture-skills/

[^27]: https://www.redhat.com/en/blog/togaf

[^28]: https://www.sciencedirect.com/topics/computer-science/the-open-group-architecture-framework

[^29]: https://theunitcompany.com/en/introduction-togaf-standard/

[^30]: https://taylorandfrancis.com/knowledge/Engineering_and_technology/Computer_science/TAFIM/

[^31]: https://www.knowledgehut.com/blog/it-service-management/togaf-architecture

[^32]: https://www.semanticscholar.org/topic/TAFIM/2606601

[^33]: https://guides.visual-paradigm.com/what-is-togaf/

[^34]: https://pubs.opengroup.org/onlinepubs/7698999699/toc.pdf

[^35]: https://estim-software.com/2023/06/20/demystifying-the-togaf-architecture-content-model-a-comprehensive-overview/

[^36]: https://www.capgemini.com/wp-content/uploads/2022/01/AGILE-IT-ARCHITECTURE_PoV.pdf

[^37]: http://www.togaf.org/togaf9/toc.html

[^38]: https://content.e-bookshelf.de/media/reading/L-2676962-ea1b01ce9d.pdf

[^39]: https://www.vinsys.com/blog/whats-new-in-togaf-10-certification

[^40]: https://cioindex.com/reference/part-1-introducing-the-open-group-architecture-framework-togaf/

[^41]: https://togaf.visual-paradigm.com/2023/10/12/a-comprehensive-guide-for-togaf-adm-phases-requirement-management-part-10/

[^42]: http://www.togaf.com/admref/_chap08.html

[^43]: https://www.knowledgehut.com/blog/it-service-management/togaf-data-architectural-way

[^44]: https://www.ealearning.com/blog/what-is-the-togaf-architecture-development-method/

[^45]: https://togaf.visual-paradigm.com/2025/02/18/comprehensive-guide-to-the-architecture-development-method-adm-in-togaf/

[^46]: https://www.theknowledgeacademy.com/blog/togaf-adm-phases-architecture-development-method/

[^47]: https://togaf.visual-paradigm.com/2023/10/12/a-comprehensive-guide-for-togaf-adm-phase-c-information-systems-architecture/

[^48]: https://www.knowledgehut.com/blog/it-service-management/togaf-adm

[^49]: https://www.scribd.com/presentation/97506927/Architecture-Framework

[^50]: https://www.opengroup.org/view-standards-information-base-historical

[^51]: https://www.slideserve.com/touchette/the-open-group-architecture-framework-togaf-version-7-powerpoint-ppt-presentation

[^52]: http://www.togaf.info/togaf9/togafSlides9/TOGAF-V9-M7-Metamodel.pdf

[^53]: http://www.cs.tlu.ee/instituut/oppe_materjalid/magister/2005/Andro_Kull/Togaf_8.pdf

[^54]: https://www.erikproper.eu/publications/jonkers2009archimatetogaf.pdf

[^55]: https://www.scitepress.org/papers/2010/29032/29032.pdf

[^56]: https://www.opengroup.org/togaf

[^57]: https://www.valueblue.com/blog/togaf-comprehensive-guide

[^58]: https://en.wikipedia.org/wiki/Enterprise_architecture_framework

[^59]: https://togaf.visual-paradigm.com/2025/01/20/comprehensive-guide-to-togaf-adm-phase-d-technology-architecture-deliverables/

[^60]: https://www.techcentral.ie/togaf-enterprise-architecture-methodology-business/

[^61]: https://coe.qualiware.com/resources/togaf/9-1/part1-introduction/definitions/

[^62]: https://insignis.be/roadmapping-part-ii/

[^63]: https://en.wikipedia.org/wiki/Business_systems_planning

[^64]: https://bura.brunel.ac.uk/bitstream/2438/5551/1/FulltextThesis.pdf

[^65]: https://cioindex.com/topic/historical-context-of-enterprise-architecture/

[^66]: http://www.bitsavers.org/pdf/ibm/generalInfo/GE20-0527-2_Information_Systems_Planning_Guide_Oct78.pdf

[^67]: https://www.ciosrc.com/blog/guide-to-planning-your-enterprise-architecture-framework/

