# Material Grid
 > Адаптивная сетка макетов Material Design адаптируется к размеру экрана и ориентации, обеспечивая согласованность между макетами.

> Сетка создает визуальную согласованность между макетами, обеспечивая при этом гибкость в широком разнообразии дизайнов. Адаптивный пользовательский интерфейс Material Design основан на сетке из 12 столбцов.
>Как это работает
Система grid реализована с помощью компонента Grid:

Он использует модуль Flexible Box от CSS для обеспечения высокой гибкости.
Существует два типа компоновки: контейнеры и элементы.
Ширина элементов задается в процентах, поэтому они всегда изменчивы и имеют размер относительно своего родительского элемента.
Элементы имеют отступы для создания интервала между отдельными элементами.
Существует пять точек останова сетки: xs, sm, md, lg и xl.
Каждой точке останова могут быть присвоены целочисленные значения, указывающие, сколько из 12 доступных столбцов занято компонентом, когда ширина видового экрана удовлетворяет ограничениям точки останова.

![](/Screenshot_6.png)
![](/Screenshot_6.png)