Программа для расчета технологических показателей месторождения для кустов/пластов/всего месторождения по каждому месяцу/году. 
Прграмма расчитывает показатели добычи нефти, жидкости и газа, количество введенных скважин, наклонно-направленных и горизонтальных скважин, количество работающих добывающих и нагнетательных скважин, количество переведенных из добывающих в нагнетательный фонд скважин, а также средний добывающий и нагнетательный фонд скважин. Значения представляются за месяц или год работы месторождения отдельно для кустов, пластов и месторождения. Также результатом программы является информация по падению дебитов скважин.

Важные примечания для работы с программой:
1. Имена столбцов исходного текстового файла должны быть:

'Name' - имя скважины.
'Well type' - тип скважины.
'Oil Rate Sm3/day' - дебит нефти скважины, м3/сут.
'Water Rate Sm3/day' - дебит жидкости скважины, м3/сут.
'Gas Rate 1000Sm3/d'  - дебит газа скважины, м3/сут.
'Oil gravity Kg/m3' - плотность нефти, кг/м3.
'Drawdown bar' - депрессия, бар.
'Date' - дата (ЧЧ.ММ.ГГГГ).
'Field' - имя пласт.
'Cluster' - имя куста.
'Cumulative Oil Production MSm3' - накопленная добыча нефти.
'Cumulative Water Production MSm3' - накопленная добыча жидкости.
'Cumulative Gas Production MSm3' - накопленная добыча газа.
2. Кодировка исходного текстового файла UTF-8.
3. Результаты сохраняются в папке с исходным файлом.

Раюота с программой:
1. При запуске программы необходимо указать путь исходного файла
2. Затем выберите способ расчета добычи. Необходимо указать номер способа: 
  1 - по дебитам скважин, 2 - по накопленным показателям (с учетом коэффициента эксплуатации).
3. Сигналом об окончании расчета является вывод программы о времени расчета.
