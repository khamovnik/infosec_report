---
## Front matter
title: "Доклад на тему 'Государственная система лицензирования. Система лицензирования в области защиты государственной тайны'"
subtitle: "Дисциплина: Информационная безопасность"
author: "Маляров Семён Сергеевич, НПИбд-01-21"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric

## Pandoc-crossref LaTeX customization
figureTitle: "Скриншот"
tableTitle: "Таблица"
listingTitle: "Листинг"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---


# Введение

Государственная система лицензирования представляет собой комплекс действий уполномоченных государственных органов, включающий в себя мероприятия по предоставлению, продлению, приостановлению и прекращению выдачи лицензий на тот или иной вид деятельности, а также непосредственное регулирование и контроль за взаимодействием между участниками лицензионного процесса.

Система государственного лицензирования строго регулируется на законодательном уровне различными федеральными законами, постановлениями и прочими нормативно-правовыми актами.

Основными принципами системы служат:
    — обеспечение прав, интересов и защиты граждан, а также способствование безопасности государства;
    — способствование целостности экономического фона на территории государства;
    — формирование и усовершенствование списка видов деятельности, которые подлежат лицензированию;
    — открытость и доступность процесса лицензирования;
    — правовое регулирование лицензирования.

# Глава 1. Лицензирование отдельных видов деятельности. Нормативно-правовая база

Опорным нормативно-правовым актом в сфере лицензирования отдельных видов деятельности является Федеральный закон от 04.05.2011 №99-ФЗ "О лицензировании отдельных видов деятельности".

В соответствии с данным законом существует перечень видов деятельности, подлежащих лицензированию, например:
    - образовательная деятельность (за исключением указанной деятельности, осуществляемой частными образовательными организациями на территории инновационного центра "Сколково");
    - оборот наркотических средств, психотропных веществ и их прекурсоров, культивирование наркосодержащих растений;
    - телевизионное вещание и радиовещание;
    - оказание услуг связи;
    - фармацевтическая деятельность;
    - медицинская деятельность (за исключением указанной деятельности, осуществляемой медицинскими организациями и другими организациями, входящими в частную систему здравоохранения, на территории инновационного центра "Сколково").
    
## Глава 1.1 Лицензирование медицинской деятельности
    
На примере лицензирования медицинской деятельности рассмотрим основные аспекты процесса лицензирования.

В соответствии с вышеуказанным Законом было утверждено Постановление Правительства РФ от 01.06.2021 г. №852 "О лицензировании медицинской деятельности (за исключением указанной деятельности, осуществляемой медицинскими организациями и другими организациями, входящими в частную систему здравоохранения, на территории инновационного центра "Сколково") и признании утратившими силу некоторых актов Правительства Российской Федерации" (с изменениями и дополнениями).

Данное Постановление утверждает Положение о лицензировании медицинской деятельности, согласно которому определен порядок лицензирования медицинской деятельности, осуществляемой на территории Российской Федерации медицинскими и иными организациями, а также индивидуальными предпринимателями, за исключением указанной деятельности, осуществляемой медицинскими организациями и другими организациями, входящими в частную систему здравоохранения, на территории инновационного центра "Сколково".

Согласно утвержденному положению лицензирование медицинской деятельности осуществляют различные органы власти в зависимости от вида учреждения, его организационно-правовой формы, подчинения.

В одном случае - Федеральная служба по надзору в сфере здравоохранения (Росздравнадзор), в другом же - уполномоченные органы исполнительной власти РФ (например, Департамент здравоохранения города Москвы).

Положение регламентирует лицензионные требования к соискателю лицензии:
    - наличие зданий, строений, сооружений и (или) помещений, принадлежащих соискателю лицензии на праве собственности или ином законном основании, необходимых для выполнения заявленных работ (услуг) и отвечающих санитарным правилам, соответствие которым устанавливается в санитарно-эпидемиологическом заключении;
    - наличие принадлежащих соискателю лицензии на праве собственности или ином законном основании, предусматривающем право владения и пользования, медицинских изделий (оборудование, аппараты, приборы, инструменты), необходимых для выполнения заявленных работ (услуг) и зарегистрированных в порядке, предусмотренном частью 4 статьи 38 Федерального закона "Об основах охраны здоровья граждан в Российской Федерации";
    - наличие заключивших с соискателем лицензии трудовые договоры работников, имеющих образование, предусмотренное квалификационными требованиями к медицинским и фармацевтическим работникам, и пройденной аккредитации специалиста или сертификата специалиста по специальности, необходимой для выполнения заявленных соискателем лицензии работ (услуг);
    - наличие заключивших с соискателем лицензии трудовые договоры работников, осуществляющих техническое обслуживание медицинских изделий (оборудование, аппараты, приборы, инструменты) и имеющих необходимое профессиональное образование и (или) квалификацию, либо наличие договора с организацией, имеющей лицензию на осуществление соответствующей деятельности;
    - соответствие структуры и штатного расписания соискателя лицензии - юридического лица, входящего в государственную или муниципальную систему здравоохранения, общим требованиям, установленным для соответствующих медицинских организаций, в соответствии с пунктом 7 части 2 статьи 14 Федерального закона "Об основах охраны здоровья граждан в Российской Федерации";
    - соответствие соискателя лицензии - юридического лица:
        - намеренного выполнять заявленные работы (услуги) по обращению донорской крови и (или) ее компонентов в медицинских целях, - требованиям, установленным статьями 15 и 16 Федерального закона "О донорстве крови и ее компонентов";
        - намеренного выполнять заявленные работы (услуги) по трансплантации (пересадке) органов и (или) тканей, - требованиям, установленным статьей 4 Закона Российской Федерации "О трансплантации органов и (или) тканей человека";
        - намеренного осуществлять медико-социальную экспертизу, - установленным статьей 60 Федерального закона "Об основах охраны здоровья граждан в Российской Федерации" и статьей 8 Федерального закона "О социальной защите инвалидов в Российской Федерации" требованиям, касающимся организационно-правовой формы юридического лица;
        - размещение в единой государственной информационной системе в сфере здравоохранения (далее - единая система) сведений о медицинской организации (в федеральном реестре медицинских и фармацевтических организаций) и о лицах, указанных в подпункте "в" настоящего пункта (в федеральном регистре медицинских и фармацевтических работников), в составе, установленном Положением о единой государственной информационной системе в сфере здравоохранения, утвержденным постановлением Правительства Российской Федерации от 09.02.2022 г. №140 "О единой государственной информационной системе в сфере здравоохранения".
        
Рекомендуемые штатные нормативы и стандарты оснащения медицинских кабинетов утверждены Приказами Минздрава РФ (Порядки оказания медицинской помощи по различным видам деятельности).

Перечень работ (услуг), составляющих медицинскую деятельность утвержден вышеуказанным Постановлением №852.

Оценка соответствия соискателя лицензии лицензионным требованиям осуществляется лицензирующим органом в соответствии с Федеральным законом "О лицензировании отдельных видов деятельности" на основании решения уполномоченного должностного лица лицензирующего органа.

Оценка соответствия соискателя лицензии производится в форме выездной оценки (в том числе с использованием средств дистанционного взаимодействия).

На основании результатов оценки соответствия соискателя лицензии принимается решение о предоставлении лицензии либо об отказе в предоставлении, однако при вынесении решения об отказе в акте оценки указывается, каким именно требованиям не соответствует соискатель лицензии.


# Глава 2. Лицензирование в области защиты государственной тайны

Государственная тайна - защищаемые государством сведения в области его военной, внешнеполитической, экономической, разведывательной, контрразведывательной и оперативно-розыскной деятельности, распространение которых может нанести ущерб безопасности Российской Федерации;

Следовательно, процесс лицензирования защиты государственной тайны должно отличаться особой строгостью выполнения норм, регламентируемых действующим законодательством.

Лицензирование осуществляется в соответствии с Законом Российской Федерации от 21.07.1993 г. №5485-I «О государственной тайне». Порядок лицензирования определен Постановлением Правительства Российской Федерации от 15.04.1995 г. №333 «О лицензировании деятельности предприятий, учреждений и организаций по проведению работ, связанных с использованием сведений, составляющих государственную тайну, созданием средств защиты информации, а также осуществлением мероприятий и (или) оказанием услуг по защите государственной тайны».

Постановление утверждает Положение о лицензировании деятельности предприятий, учреждений и организаций по проведению работ, связанных с использованием сведений, составляющих государственную тайну, созданием средств защиты информации, а также с осуществлением мероприятий и (или) оказанием услуг по защите государственной тайны.

Лицензии (в части услуг в области защиты государственной тайны, оказываемых режимно-секретным подразделением, а также в части функционирования шифровального органа) предоставляет Центр по лицензированию, сертификации и защите государственной тайны ФСБ России, а также территориальные органы безопасности по месту осуществления заявителем заявленного вида деятельности.

На орган, уполномоченный на ведение лицензионной деятельности, возлагается:
    - организация лицензирования деятельности предприятий;
    - организация и проведение специальных экспертиз предприятий;
    - рассмотрение заявлений предприятий о выдаче лицензий;
    - принятие решений о выдаче или об отказе в выдаче лицензий;
    - выдача лицензий;
    - принятие решений о приостановлении действия лицензии или о ее аннулировании;
    - разработка нормативно-методических документов по вопросам лицензирования;
    - привлечение в случае необходимости представителей министерств и ведомств Российской Федерации для проведения специальных экспертиз;
    
Работа органов, уполномоченных на ведение лицензионной деятельности, координируется Межведомственной комиссией по защите государственной тайны.

Межведомственная комиссия по защите государственной тайны является коллегиальным органом, координирующим деятельность органов государственной власти по защите государственной тайны в интересах разработки и выполнения государственных программ, нормативных и методических документов, обеспечивающих реализацию законодательства Российской Федерации о государственной тайне. 

Лицензия оформляется на бланке, имеющем степень защиты на уровне степени защиты ценной бумаги. Бланки лицензий являются документами строгой отчетности, имеют учетную серию и номер. 

Для получения лицензии заявитель представляет в соответствующий орган уполномоченный на ведение лицензионной деятельности, следующие документы:
        - заявление о выдаче лицензии с указанием:
            - наименования, организационно-правовой формы и местонахождения предприятия;
            - идентификационного номера налогоплательщика;
            - даты уплаты предприятием государственной пошлины за предоставление лицензии;
            - сведений о наличии допуска к государственной тайне у руководителя предприятия;
            - адресов мест осуществления лицензируемого вида деятельности;
            - реквизитов правоустанавливающих документов на объекты недвижимости, необходимые для осуществления заявленного вида деятельности на срок действия лицензии, права на которые зарегистрированы в Едином государственном реестре прав на недвижимое имущество и сделок с ним;
            - вида деятельности, на осуществление которого должна быть выдана лицензия;
            - срока действия лицензии;
            - степени секретности сведений, составляющих государственную тайну, с которыми заявитель предполагает осуществлять работы, подтвержденной органом государственной власти или организацией, наделенными полномочиями по распоряжению указанными сведениями;
            - формы предоставления лицензии (на бумажном носителе или в электронной форме (в форме электронного документа, подписанного электронной подписью));
        - копии учредительных документов юридического лица;
        - копии правоустанавливающих документов на объекты недвижимости, необходимые для осуществления заявленного вида деятельности на срок действия лицензии, права на которые не зарегистрированы в Едином государственном реестре прав на недвижимое имущество и сделок с ним;
        - копия договора об оказании услуг (в случае использования заявителем услуг структурного подразделения по защите государственной тайны другой организации).
        
В лицензии указывается следующая информация:
    - наименование органа, выдавшего лицензию;
    - наименование, место нахождения предприятия, адреса мест осуществления лицензируемого вида деятельности (при необходимости), в том числе адреса мест осуществления лицензируемого вида деятельности подразделениями предприятия;
    - идентификационный номер налогоплательщика;
    - вид деятельности, на осуществление которого выдана лицензия;
    - условия осуществления вида деятельности, на который выдана лицензия;
    - степень секретности разрешенных к использованию сведений, составляющих государственную тайну, для лицензии на проведение работ, связанных с использованием сведений, составляющих государственную тайну;
    - срок действия лицензии;
    - регистрационный номер и дата выдачи лицензии.

Срок действия лицензии устанавливается в зависимости от специфики вида деятельности, но не более чем на 5 лет. 

Орган, уполномоченный на ведение лицензионной деятельности, вправе отказать в выдаче лицензии. Письменное уведомление об отказе в выдаче лицензии с указанием причин отказа направляется заявителю в 3-дневный срок после принятия соответствующего решения.

Основанием для отказа в выдаче лицензии является:
    - наличие в документах, представленных заявителем, недостоверной или искаженной информации;
    - отрицательное заключение экспертизы, установившей несоответствие необходимым для осуществления заявленного вида деятельности условиям, указанным в  Положении;
    - отрицательное заключение по результатам государственной аттестации руководителя предприятия.
    
Государственными органами, ответственными за организацию и проведение специальных экспертиз предприятий, являются Федеральная служба безопасности Российской Федерации, Федеральная служба по техническому и экспортному контролю, Служба внешней разведки Российской Федерации, Министерство обороны Российской Федерации, другие министерства и ведомства Российской Федерации и Государственная корпорация по атомной энергии "Росатом", руководители которых наделены полномочиями по отнесению к государственной тайне сведений в отношении подведомственных им предприятий.

Организация и порядок проведения специальных экспертиз предприятий определяются инструкциями, которые разрабатываются указанными государственными органами и согласовываются с Межведомственной комиссией.

Органы, уполномоченные на ведение лицензионной деятельности, приостанавливают действие лицензии или аннулируют ее в случае:
        - предоставления лицензиатом соответствующего заявления;
        - обнаружения недостоверных данных в документах, представленных для получения лицензии;
        - нарушения лицензиатом условий действия лицензии;
        - невыполнения лицензиатом предписаний или распоряжений государственных органов или приостановления этими государственными органами деятельности предприятия в соответствии с законодательством Российской Федерации;
        - ликвидации предприятия.


# Заключение

Государственная система лицензирования является важным элементом упорядочивания деятельности различных учреждений на территории РФ. Регламенты, утвержденные соответствующими Законами, Постановлениями, Положениями, позволяют беспристрастно и объективно оценивать соответствие соискателя лицензии лицензионным требованиям. 

Лицензирование в области защиты государственной тайны является серьезным процессом с точки зрения соблюдением интересов национальной безопасности государства. 

В заключение можно отметить, что  эффективность системы лицензирования  зависит  от  сочетания  правовых  норм,  технологических  решений  и  высокой  ответственности  всех  участников  процесса  обращения  с  государственной  тайной. 

# Список литературы

1. Федеральный закон от 04.05.2011 №99-ФЗ "О лицензировании отдельных видов деятельности" // https://base.garant.ru/12185475/?ysclid=m0vawasoke454426878 (дата обращения: 09.09.2024)

2. Постановление Правительства РФ от 01.06.2021 г. №852 "О лицензировании медицинской деятельности (за исключением указанной деятельности, осуществляемой медицинскими организациями и другими организациями, входящими в частную систему здравоохранения, на территории инновационного центра "Сколково") и признании утратившими силу некоторых актов Правительства Российской Федерации" (с изменениями и дополнениями) // https://base.garant.ru/400846456/ (дата обращения: 09.09.2024)

3. Закон РФ от 21 июля 1993 г. №5485-I "О государственной тайне" (с изменениями и дополнениями) // https://base.garant.ru/10102673/ (дата обращения: 09.09.2024)

4. Постановление Правительства РФ от 15.04.1995 №333 (ред. от 26.10.2023) "О лицензировании деятельности предприятий, учреждений и организаций по проведению работ, связанных с использованием сведений, составляющих государственную тайну, созданием средств защиты информации, а также с осуществлением мероприятий и (или) оказанием услуг по защите государственной тайны" // https://www.consultant.ru/document/cons_doc_LAW_6387/ (дата обращения: 09.09.2024)

5. Общая информация по лицензированию // http://clsz.fsb.ru/clsz/license.htm (дата обращения: 09.09.2024)
