# Exoplanets Data Analytics
## Аналитическая работа по открытым экзопланетам с использованием python, pandas, matplotlib, numpy.

На 5 мая таблица всех экзопланет содержала 7013 записей. Каждой из этих планет, находящихся вне нашей Солнечной системе были даны определённые разные имена. Которые впрочем часто дублируют название звезды с добавлением какой то буквы.
Все планеты делятся по статусу:

![Статус экзопланет](/pics/Статус_экзопланет_на_май_2020_года.png)

За время проведения исследования часть планет перешло из кандидатов в подтверждённые.

![Распределение пустых значений](/pics/Распределение_пустых_значений_в_информации.png)

В базе данных экзопланет множество незаполненных значений. Это связано с тем, что не всю информацию удалось получить или рассчитать из-за определённых помех при наблюдении планеты. Практически все параметры планет имеют пробелы, почти для всех планет известно название звезды вокруг которой она обращается, для примерно половины известна масса, но более сложные показатели такие как угол лямбда известны у меньшинства планет.

![Количество звёзд с планетами](/pics/Количество_звёзд_с_планетами.png)

![Распределение планет по разрядности их звёздных систем](/pics/Распределение_планет_по_разрядности_их_звёздных_систем.png)

Большинство открытых экзопланет единственные в системе со звездой. Это связано с тем, что открыты наибольшие планеты в системе, а также невозможностью на данном этапе открытия дополнительных планет в их системах. То есть говорить о том, что большинство звёзд имеют одну планету спутник пока рано. Касательно многопланетных систем сохраняется закономерность: чем больше планет имеет звезда, тем меньше таких звёзд. 9-планетная система лишь одна - HD 10180 (но точно подтверждено в ней только 7).
Перейдём к информации о только подтверждённых экзопланетах. Наиболее интересны наибольшие и наименьшие показатели по различным категориям.

## Масса
Подтверждённых планет, с заполненными полями столбца масса: 1238
Самая большая масса у экзопланет: <br />
Экзопланета | Масс Юпитера 
--- | ---
HD 87883 b | 81.90
HD 1160 b | 79.00
6 Lyn b | 68.80
2M1059-21 b | 66.95
2M0805+48 b	| 66.28

Самая маленькая масса у экзопланет: <br />
Экзопланета | Масс Земли
--- | ---
WD 1145+017 b |	0.00067
Kepler-1520 b | 0.02
PSR 1257 12 b | 0.022
Kepler-138 b | 0.067
TRAPPIST-1 h | 0.331

Почти такую же массу как и Земля имеют:<br />
Экзопланета | Масс Земли
--- | ---
Kepler-138 c | 1.001
Kepler-42 d | 1
EPIC 248545986 c | 0.9
KOI-2700 b | 0.86
TRAPPIST-1 b | 0.86
 
Экзопланет масса которых больше чем имеет Земля: 1222<br />
Экзопланет масса которых меньше чем имеет Земля: 16<br />
Экзопланет масса которых больше чем имеет Земля в 76.38 раз больше<br />

![Соотношение массы к расстоянию](/pics/Соотношение_массы_открытых_экзопланет_к_расстоянию_до_них.png)

Большинство экзопланет, которые мы открыли конечно находятся рядом. Поэтому почти все планеты расположились в левой части графика, до 2000 парсек. В общем то все видные кружки это крупные по массе планеты, учитывая что наша Земля это 1. Можно заметить очевидную зависимость – чем дальше, тем меньше экзопланет открыто. А также неочевидную зависимость – большинство открытых экзопланет крупнее по массе Земли в сотни-тысячу раз. 

![Соотношение радиуса и массы](/pics/Соотношение_радиуса_и_массы_экзопланеты.png)

Можно отметить, что большинство планет имеют радиус в промежутке от 0 до 2 радиусов Юпитера. В то время как по массе планеты значительно более разнообразны. 

## Радиус
Подтверждённых планет, с заполненными полями столбца радиус: 3137<br />
Самый большой радиус у экзопланет:<br />
Экзопланета | Радиусов Юпитера
--- | ---
V* V2384 Ori a | 6.52
V* V2384 Ori b | 4.81
USco1610-1913 b | 3.87
HD108236 e | 3.12
TYC 8998-760-1 b | 3.00

Самый маленький радиус у экзопланет: <br />
Экзопланета | Радиусов Земли
--- | ---
1I/'Oumuamua | 0.00002
2I/Borisov | 0.0007
SDSS J1228+1040 b | 0.01
Kepler-391 b | 0.285
Kepler-37 b | 0.32
<br />
1I/'Oumuamua это астероид пролетавший через Солнечную систему в 2017 году. 2I/Borisov также межзвёздная комета, проходившая Солнечную систему в 2019 году.

Такой же радиус как и Земля имеют:<br />
Экзопланета | Радиусов Земли
--- | ---
Kepler-1288 b |	1
Kepler-285 c | 1
Kepler-1082 b | 1
Kepler-334 b | 1
Kepler-1164 b | 1

Эти планеты, открытые «Кеплером», из разных планетных систем. <br />
Экзопланет радиус которых больше чем имеет Земля: 2891<br />
Экзопланет радиус которых меньше чем имеет Земля: 237<br />
Экзопланет радиус которых больше чем имеет Земля в 12.20 раз больше<br />

Большинство планет имеет больший чем Земля радиус. Вероятнее всего это связано также с открытием только самых больших планет на данном этапе.<br />

![Соотношение радиуса к расстоянию](/pics/Соотношение_радиуса_открытых_экзопланет_к_расстоянию_до_них.png)

Из следующей диаграммы становится понятно, что основная часть открытых планет вне зависимости от размера находится в пределах 2000 парсек. Но есть и два исключения SWEEPS 04 b и 11 – это планеты расположенные недалеко от центра нашей галактики, одни из самых далёких из известных на данный момент. По радиусу сравнимы с Юпитером.

## Орбитальный период в днях
Подтверждённых планет, с заполненными полями столбца орбитальный период: 4020<br />
Орбитальный период это время, за которое тело совершает полный оборот вокруг звезды. Орбитальный период Земли соответственно равен 365,256 дней. <br />

Самый большой орбитальный период у экзопланет:<br /> 
Экзопланета | Орбитальный период
--- | ---
11 Oph b | 2000 лет
Fomalhaut b | 876,7 лет
kappa And b |	589 лет
HR 8799 b | 450 лет
WISE 1711+3500 b | 342,4 лет
<br />
Да, планета 11 Oph b делает полный оборот вокруг звезды 11 Oph за 2000 лет.
<br />

Самый маленький орбитальный период у экзопланет: <br /> 
Экзопланета | Орбитальный период
--- | ---
XTE J1807-294 b | 40 минут
XTE J1751-305 b |	42 минуты
GP Com b | 46 минут
J1433 b | 1 час 17 минут
PSR 0636 b | 1 час 36 минут
<br />

Почти такой же орбитальный период как и Земля имеют: <br /> 
Экзопланета | Орбитальный период
--- | ---
Kepler-1536 b |	364.758031
HD 47366 b | 363.300000
HD 38283 b | 363.200000
HD 96063 b | 361.100000
HD 4732 A b | 360.200000
<br /> 
Экзопланет орбитальный период которых больше чем имеет Земля: 520<br /> 
Экзопланет орбитальный период которых меньше чем имеет Земля: 3500<br /> 
Экзопланет орбитальный период которых меньше чем имеет Земля в 6.73 раз больше<br /> 
Большинство планет вращается вокруг своих звёзд быстрее Земли. Это может быть связано с тем, что планету проще обнаружить, если они находится ближе к звезде, и соответственно быстрее вокруг неё вращается.<br /> 

## Большая полуось
Подтверждённых планет, с заполненными полями столбца большая полуось: 2729<br /> 
Большая полуось выраженная в астрономических единицах это расстояние а (максимальное расстояние от звезды до планеты) на картинке (наибольший радиус эллипса орбиты). Земное расстояние до Солнца принято за эталонное и равняется 1 астрономической единице (хотя земная орбита ближе к кругу чем изображение ниже).<br /> 

![Большая полуось](https://upload.wikimedia.org/wikipedia/commons/a/a1/Ellipse_semi-major_and_minor_axes.svg)

Самая большая полуось у экзопланет:<br /> 
Экзопланета | Большая полуось
--- | --- 
HD 118865 B | 9200
2M J2126-81 b | 6900
beta Cir b | 6656
USco 1556A b | 3500
HIP 77900 b | 3200
<br />
Этих планет расстояние до родительской звезды которых превосходит расстояние Земля-Солнце в тысячи раз, открыто не так много. Точно неизвестно, почему они находятся на таком чрезвычайно далёком расстоянии от своей звезды.<br /> 

Самая маленькая большая полуось у экзопланет: <br /> 
Экзопланета | Большая полуось
--- | --- 
NLTT 5306 b | 0.00263
WD 0137-349 b | 0.00300
SDSS J1228+1040 b | 0.00340
PSR 1719-14 b | 0.00440
PSR J1544+4937 b | 0.00537
<br />

Почти такая же большая полуось как и Земля: <br /> 
Экзопланета | Большая полуось
--- | --- 
HIP 57274 d | 1.010
BD+48 738 b | 1.000
WISE J0458+6434  A | 1.000
30 Ari B b | 0.995
HD 148164 c | 0.993
<br /> 
Экзопланет большая полуось которых больше чем имеет Земля: 652<br /> 
Экзопланет большая полуось которых меньше чем имеет Земля: 2077<br /> 
Экзопланет большая полуось которых меньше чем имеет Земля в 3.19 раз больше<br /> 

![Масса к большой полуоси](/pics/Масса_экзопланеты_по_отношению_к_большой_полуоси.png)<br />
Как сказано выше, планеты близкие к своим звёздам и большие обнаружить проще. Что и доказывает информация выше: большинство открытых планет больше Земли, но находятся ближе к своей звезде.

## Эксцентриситет
Подтверждённых планет, с заполненными полями столбца эксцентриситет: 1642<br />
Самый большой эксцентриситет у экзопланет: <br />
Экзопланета | Эксцентриситет
--- | --- 
2I/Borisov | 3.15500
1I/'Oumuamua | 1.19600
HD 20782 b | 0.97000
HD 80606 b | 0.93366
HD 7449 A b | 0.92000

Самый маленький эксцентриситет у экзопланет: <br />
Экзопланета | Эксцентриситет
--- | --- 
WASP-106 b | 0
WASP-151 b | 0
GJ 9827 d | 0
GJ 9827 b | 0
WASP-96 b | 0
<br />

Почти такой же эксцентриситет как и Земля имеют: <br />
Экзопланета | Эксцентриситет
--- | --- 
Pr 0211 b | 0.017
WASP-124 b | 0.017
Kepler-411 e | 0.016
HAT-P-22 b | 0.016
NGTS-1 b | 0.016
<br />
Экзопланет эксцентриситет которых больше чем имеет Земля: 1249<br />
Экзопланет эксцентриситет которых меньше чем имеет Земля: 393<br />
Экзопланет эксцентриситет которых больше чем имеет Земля в 3.18 раз больше<br />
Эксцентриситет равный 0 это круговая орбита. 320 планет имеют такую орбиту. Наша земная орбита также не сильно далека от круга, но большая часть открытых планет имеют больший эксцентриситет, то есть их орбиты отклоняются больше в сторону эллиптических.<br />

## Наклонение
![Наклонение](https://upload.wikimedia.org/wikipedia/commons/5/5b/Orbit_ru.svg)<br />
Наклонение это угловой показатель отражающий насколько сильно плоскость орбиты отклонена от плоскости эклиптики (экватором центрального тела). Для Земли наклонение принято за 0 градусов. <br />
Подтверждённых планет, с заполненными полями столбца наклонение: 966<br />
Самое большое наклонение у экзопланет: <br />
Экзопланета | Наклонение
--- | --- 
gamma 1 Leo b | 172.1
HD 106252 b | 166.7
HD 136118 b | 163.1
HD 95086 b | 153.0
HD 206893 b | 150.0

Самое маленькое наклонение у экзопланет: <br />
Экзопланета | Наклонение
--- | --- 
Wolf 503 b | -2.00
HD 181720 b | 1.75
6 Lyn b | 2.00
HD 190228 b | 4.50
HD 202206 (AB) c | 7.70

### Прямая и ретроградная орбита
Наклонение обозначается как ***i***.

Если 0 < ***i*** < 90, то движение небесного тела называется прямым.<br />
Если 90 < ***i*** < 180, то движение небесного тела называется обратным.<br />

Экзопланет наклонение которых больше чем 90 градусов: 23<br />
Экзопланет наклонение которых меньше чем 90 градусов: 933<br />
У 10 планет наклонение равно 90 градусам.<br />
Получается, что большинство планет имеют всё таки прямое движение: звезда вращается вокруг своей оси в том же направлении в котором и планета вращается вокруг звезды. 23 открытым планетам свойственно ретроградное вращение, показанное на гифке (звезда вращается вокруг своей оси, планета вращается вокруг звезды в противоположную сторону).<br />

![Ретроградная орбита](https://upload.wikimedia.org/wikipedia/commons/6/65/Retrogradeorbit.gif)<br />

У 10 планет наклонение равно 90 градусам.<br />
![Углы лямбда](/pics/Распределение_углов_лямбда_экзопланет.png)<br />

Эти планеты лежат перпендикулярно плоскости вращения звезды вокруг своей оси. Таким образом планета проходит через полюса звезды. Чтобы проще представить такое движение, можно ознакомится с понятием полярной орбиты. <br />
Можно сделать вывод о том, что большинство планет имеют прямую орбиту вращения. Маленькая часть имеет ретроградную, и совсем исключениями являются полярные орбиты.<br />
Распределение углов наклонения среди экзопланет показывает насколько редки планеты с ретроградной орбитой вращения. Но также можно заметить большое количество планет орбита вращения которых достаточно близка к полярной.<br />

![Распределение углов наклонения](/pics/Распределение_углов_наклонения_экзопланет.png)<br />

## Угловое расстояние
Угловое расстояние это угол точками которого являются два объекта: планета и звезда, а вершиной наблюдатель. В таблице выражен в секундах дуги.<br />
Подтверждённых планет, с заполненными полями столбца угловое расстояние: 661<br />

Самое большое угловое расстояние у экзопланет: <br />
Экзопланета | Угловое расстояние
--- | --- 
WD 0806-661 B b | 130.208333
HN Peg b | 43.206522
Fomalhaut b | 14.927310
Ross 458 (AB) c | 10.245614
SR 12 (AB) c | 8.664000

Самое маленькое угловое расстояние у экзопланет:<br />
Экзопланета | Угловое расстояние
--- | --- 
SWEEPS-11 b | 0.000004
Kepler-70 b | 0.000005
Kepler-70 c | 0.000006
SWEEPS-04 b | 0.000006
OGLE-TR-113 b | 0.000015

## Год открытия
Подтверждённых планет, с заполненными полями столбца открытие: 4260<br />
Среди открытых в 2020 году планеты: OGLE-2017-BLG-0406 b,  TOI-700 b, TOI-849 b,   HD108236 e и т. д.<br />
Одними из первых открытых экзопланет являются: PSR B1957+20 b (1988), PSR 1257 12 b (1992), PSR 1257 12 c (1992),  PSR 1257 12 d (1992), Teide 1 (1995).<br />

![Открытие экзопланет по годам](/pics/Открытие_экзопланет_по_годам.png)<br />
![Отношение массы к году открытия](/pics/Отношение_массы_планеты_к_году_открытия.png)<br />

## Аргумент перицентра
![Аргумент перицентра](https://upload.wikimedia.org/wikipedia/commons/5/5b/Orbit_ru.svg)<br />

Аргумент перицентра представляет собой угол между линией плоскости экватора центрального тела и линией перицентра по плоскости орбиты.<br />
Подтверждённых планет, с заполненными полями столбца аргумент перицентра: 1007<br />
Среди планет с самым большим аргументом перицентра (360 градусов) экзопланеты: HD 37124 d, GJ 876 e, Kepler-102 e.<br />
Самый маленький аргумент перицентра у экзопланет: Kepler-130 c (0), HD 1397 b (0.1), MARVELS-10 b (0.1), GJ 674 b (0.5), BD+26 1888 b (1.3).<br />

![Аргументы перицентра](/pics/Распределение_аргументов_перицентра.png)<br />

Аргументы перицентра планет распределены равномерно. <br />

## Лямбда угол
Угол между плоскостью орбиты планеты и осью вращения звезды.<br />

Подтверждённых планет, с заполненными полями столбца угол лямбда: 66<br />
Самый большой угол лямбда у экзопланет:<br />

Экзопланета | Лямбда угол
--- | --- 
WASP-84 b | 359.70
EPIC 246851721 b | 358.52
WASP-166 b | 357.00
WASP-66 b | 356.00
WASP-87 A b | 352.00

<br />
Самый маленький угол лямбда у экзопланет: <br />

Экзопланета | Лямбда угол
--- | --- 
HD 63433 b | 1.0
Kepler-1115 b | 1.0
K2-29 b | 1.5
MASCARA-2 b/KELT-20 b | 1.6
KELT-1 b | 2.0

<br />

![Углы лямбда](/pics/Распределение_углов_лямбда_экзопланет.png)<br />

## Вычисленная температура
Подтверждённых планет, с заполненными полями столбца температура вычисленная: 516<br />
Самая высокая вычисленная температура у экзопланет: <br />

Экзопланета | Вычисленная температура
--- | --- 
HD 195689 b | 3647,85
TOI-402 b | 2835,85
USco1602-2401 b | 2516,85
WASP-33 b | 2508,85
HATS-70 b | 2456,85
<br />

Самая низкая вычисленная температура у экзопланет: <br />
Экзопланета | Вычисленная температура
--- | --- 
Proxima Centauri c | -234,15
Barnard's  b | -168,15
HR 5183 b | -163,15
Kepler-167 e | -142,15
HD 164922 b | -114,15
<br />

Почти такая же вычисленная температура как и на Земле: <br />
Экзопланета | Вычисленная температура
--- | --- 
TOI-700 d | 21,85
Kepler-90 h | 18,85
K0I-1783 c | 16,85
TRAPPIST-1 d | 14,85
Kepler-86 b | 7,85
<br />
Экзопланет температура вычисленная которых больше чем имеет Земля: 483<br />
Экзопланет температура вычисленная которых меньше чем имеет Земля: 33<br />
Экзопланет температура вычисленная которых больше чем имеет Земля в 14.64 раз больше<br />
 
Подтверждённых планет, с заполненными полями столбца температура измеренная: 44<br />

Самая высокая измеренная температура: <br />
Экзопланета | Измеренная температура
--- | --- 
PZ Tel b | 2714
LSR J1835 | 2527
Kepler-13 A b | 2477
HD 984 b | 2457
HIP 78530 b | 2406
<br />

Самая низкая измеренная температура: <br />
Экзопланета | Измеренная температура
--- | --- 
Qatar-3 b | -188
CWISEP J1935-1546 | 62
WISE 1217+16 A b | 177
WISE 1711+3500 b | 187
GJ 504 b | 271
<br />
Экзопланет температура измеренная которых больше чем имеет Земля: 43<br />
Экзопланет температура измеренная которых меньше чем имеет Земля: 1<br />

![Температура и расстояние](/pics/Зависимость_температуры_на_планете_от_расстояния_до_звезды.png)<br />

![Температура и радиус](/pics/Зависимость_температуры_от_радиуса_экзопланеты.png)<br />

## Геометрическое альбедо
Отношение его фактической яркости, видимой от источника света (то есть под нулевым фазовым углом), к идеализированной полностью отражающей плоскости. <br />
Земля имеет геометрическое альбедо 0.434.<br />
Подтверждённых планет, с заполненными полями столбца геометрическое альбедо: 12<br />
Самый большой показатель у Kepler-1658 b - 0.785, самый маленький WASP-104 b - 0.030.<br />
Почти такое же геометрическое альбедо как и Земля имеет HD 189733 b - 0.40. <br />
Экзопланет геометрическое альбедо которых больше чем имеет Земля: 3<br />
Экзопланет геометрическое альбедо которых меньше чем имеет Земля: 9<br />

![Геометрическое альбедо](/pics/Геометрическое_альбедо.png)<br />
![Разница в геом альбедо](/pics/Разница_в_геометрическом_альбедо_экзопланет.png)<br />

## Поверхностная гравитация
1g = 9,81 м/с2, ускорение свободного падения на Земле.<br />
Подтверждённых планет, с заполненными полями столбца поверхностная гравитация: 26<br />
Самая большая поверхностная гравитация у экзопланеты LHS 2397a B - 5.35 g.<br />
Самая маленькая поверхностная гравитация у экзопланеты HAT-P-18 b - 2.734 g.<br />
Экзопланет поверхностная гравитация которых больше чем имеет Земля: 26<br />
Экзопланет поверхностная гравитация которых меньше чем имеет Земля: 0<br />

![Поверхностная гравитация](/pics/Поверхностная_гравитация_экзопланет.png)<br />
![Зависимость гравитации от массы](/pics/Зависимость_поверхностной_гравитации_от_массы_экзопланет.png)<br />

## Публикационный статус
![Публикационный статус](/pics/Публикационный_статус.png)<br />

## Тип обнаружения
![Тип обнаружения](/pics/Экзопланеты_по_типу_обнаружения.png)<br />
![Тип обнаружения](/pics/Открытые_экзопланеты_по_типу_обнаружения.png)<br />
![Тип обнаружения](/pics/Открытие_экзопланет_по_годам_2.png)<br />
![Тип обнаружения](/pics/Открытие_экзопланет_по_годам_3.png)<br />


## Тип измерения массы планет
![Тип обнаружения массы](/pics/Экзопланеты_по_типу_обнаружения_массы.png)<br />
![Тип обнаружения массы](/pics/Открытые_экзопланеты_по_типу_обнаружения_массы.png)<br />

## Тип измерения радиуса планет
![Тип измерения радиуса](/pics/Экзопланеты_по_типу_измерения_радиуса.png)<br />
![Тип измерения радиуса](/pics/Экзопланеты_по_типу_измерения_радиуса_по_годам.png)<br />

## Альтернативные имена
514 планет имеют несколько имён. В среднем планеты с несколькими именами имеют 3,2 имени.<br />

## Молекулы
У 76 планет найдены молекулы.
![Молекулы](/pics/Молекулы_по_количеству_планет_на_которых_они_обнаружены.png)<br />

## Металличность звезды
Подтверждённых планет, с заполненными полями столбца металличность звезды: 3673<br />
Экзопланет металличность звезды которых больше чем имеет Солнце: 1714<br />
Экзопланет металличность звезды которых меньше чем имеет Солнце: 1946<br />

![Металличность](/pics/Зависимость_металличности_звезды_от_расстояния_до_неё.png)<br />

## Масса звезды
Подтверждённых планет, с заполненными полями столбца масса звезды: 3827<br />
Экзопланет масса звезды которых больше чем имеет Солнце: 1634<br />
Экзопланет масса звезды которых меньше чем имеет Солнце: 2100<br />

![Зависимость массы звезды от расстояния](/pics/Зависимость_массы_звезды_от_расстояния_до_неё.png)<br />

## Радиус звезды
Подтверждённых планет, с заполненными полями столбца радиус звезды: 3677<br />
Экзопланет радиус звезды которых больше чем имеет Солнце: 1772<br />
Экзопланет радиус звезды которых меньше чем имеет Солнце: 1853<br />

![Зависимость радиуса звезды от расстояния](/pics/Зависимость_радиуса_звезды_от_расстояния_до_неё.png)<br />

## Возраст звезды в миллиардах лет
Подтверждённых планет, с заполненными полями столбца возраст звезды: 1275<br />
Старше Солнце: 528<br />
Младше Солнца: 740<br />

![Зависимость возраста звезды от расстояния](/pics/Зависимость_возраста_звезды_от_расстояния_до_неё.png)<br />

















