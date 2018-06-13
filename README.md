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
