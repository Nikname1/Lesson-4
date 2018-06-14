# Lesson-4
Лабораторная работа № 4.1
Вывод нечётных чисел из заданного диапазона от 1до 50
<?php 
for($i=1;$i<51;$i++){
//Выводим нечётные числа
echo "$i<br>";
$i+=1;
}
?>
Лаборатоная работа №4.2
Создать переменнуб $var и присвоить ей сторковое значение HELLO
<?php 
$var="HELLO";
$i=0;
while($i<5){
echo $var{$i},'<br/>';
$i++;
}
?>
Лаборатоная работа №4.3
Создание динамической таблицы умножения.
<?php
$rows = 10; // количество строк, tr
$cols = 10; // количество столбцов, td
$background = 'brown';
$table = '<table border="1">';
for ($tr=1; $tr<=$rows; $tr++){
$table .= '<tr>';
for ($td=1; $td<=$cols; $td++){
$table .= '<td>'. $tr*$td .'</td>';
}
$table .= '</tr>';
}
$table .= '</table>';
echo $table; // 
 ?>
Лабораторная работа №4.1
Выод меню с использованием цикла
<?php
$leftMenu=array(
array('link'=>'Домой','href'=>'index.php'),
array('link'=>'О нас','href'=>'about.php'),
array('link'=>'Контакт','href'=>'contact.php'),
array('link'=>'Таблица','href'=>'table.php'),
array('link'=>'Калькулятор','href'=>'calc.php')
);
//Инициализация  массива
foreach ($leftMenu as $item) { 
echo "<ul>";
echo "<li>";
echo "<a href='{$item['href']}'>{$item['link']}</a>"; 
echo "</li>";
echo "</ul>";
}
?>
Over
