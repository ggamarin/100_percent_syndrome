# Счетчики покрытия тестами

JaCoCo использует ряд счетчиков для определения величины покрытия тестами кода. В ДЗ исследованы три из них:

### INSTRUCTION

Наименьшая единица измерения, предоставляет информацию, какое количество инструкций байт-кода выполнено или пропущено.

### BRANCH

Метрика подсчитывает общее количество ветвей if и switch и определяет количество выполненных или пропущенных веток.
Предусмотрено три состояния:
* Нет покрытия: не было выполнено ни одной ветки (красный ромб)
* Частичное покрытие: была выполнена только часть ветвей (желтый ромб)
* Полный охват: все ветки были выполнены (зеленый ромб)
 
### LINE

Для всех скомпилированных файлов классов можно рассчитать покрытие для отдельных строк. Строка считается выполненной, 
если выполнена хотя бы одна инструкция в ней. Предусмотрено три состояния:
* Нет покрытия: в строке не было выполнено никаких инструкций (красный фон)
* Частичное покрытие: была выполнена только часть инструкции в строке (желтый фон)
* Полный охват: все инструкции в строке были выполнены (зеленый фон) 