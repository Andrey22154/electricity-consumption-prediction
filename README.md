# electricity-consumption-prediction
Обеспечение энергетической гибкости предприятий минерально-сырьевого 
комплекса и реализация ценозависимого потребления может быть достигнута за счет 
внедрение промышленных систем накопления электроэнергии (СНЭЭ), распределенной 
генерации (РГ), а также систем интеллектуального управления энергопотреблением. 
Для формирования оптимальных управляющих воздействий для СНЭЭ и РГ 
требуется выполнение качественного прогнозирования электрической нагрузки. Это 
позволит снизить потребление из сети электрической энергии в часы пиковой нагрузки 
(плановые часы пиковой нагрузки, час максимального совокупного потребления 
электроэнергии в субъекте Российской Федерации), а также планировать 
электропотребление на месяц вперед для расчета по 6-й ценовой категории. Более высокое 
качество прогноза потребления электрической энергии позволяет более эффективным 
образом задействовать СНЭЭ и РГ, а, следовательно, получать большую выгоду от их 
использования.
В данных есть 4 признака:
1) Traffic_flow - Грузопоток ленточного конвейера, т/час
2) Haulage_speed - Скорость подачи комбайна, м/мин
3) Power - Потребляемая мощность (по одной фазе) очистным комбайном, перегружателем и дробилкой, кВт
4) DateTime - Дата и время текущей записи

Выемочный участок работает в трехсменном режиме: 
1-я смена (ремонтная) – с 9-00 до 17-00; 

2-я смена – с 17-00 до 01-00; 

3-я смена – с 01:00 до 9-00.
