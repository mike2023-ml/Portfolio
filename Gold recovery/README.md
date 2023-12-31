## "Исследование технологического процесса очистки золота"
[`ipynb`](https://github.com/mike2023-ml/Portfolio/blob/44d34f3bbc5a931a8ee106600ead205a610a1eff/Gold%20recovery/Восстановление%20золота.ipynb)  

**Задачи проекта:**  
*Спрогнозировать концентрацию золота при проведении процесса очистки золота.*

***

**Описание проекта:**  
*Строится модель машинного обучения для промышленной компании, разрабатывающая решения для эффективной работы промышленных предприятий. Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды на основе данных с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.*

***

**Выводы по проекту:**  

*В целях решения поставленных задач:*
- *была проверена правильность расчета эффективности обогащения;*
- *исследованы изменение концентрации металлов (Au, Ag, Pb) на различных этапах очистки, а также суммарная концентрация всех веществ на разных стадиях: в сырье, в черновом и финальном концентратах;*
- *построены модели ML и выбрана наилучшая по метрике sMAPE, которая была проверена на тестовой выборке.*

*Лучший результат метрики итоговой sMAPE показала модель RandomForestRegressor.   
При проверке на вменяемость выбранная нами модель RandomForestRegressor показала результат лучше случайного, модель может применяться.*

***
    
**Инструменты:**  

`Python` `Pandas` `Scikit-learn` `NumPy` `Seaborn` `Matplotlib` `исследовательский анализ данных`

***

**Если проект не открывается, его можно просмотреть по ссылке:**  

[`nbviewer`](https://nbviewer.org/github/mike2023-ml/Portfolio/blob/main/Gold%20recovery/Восстановление%20золота.ipynb#Функция-для-вычисления-итоговой-sMAPE)    
</div>
