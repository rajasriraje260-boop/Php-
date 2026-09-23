<?php

$marks = array(85, 78, 92, 67, 88);

$total = array_sum($marks);
$average = $total / count($marks);
$highest = max($marks);
$lowest = min($marks);

echo "Student Marks Management<br>";
echo "Marks: ";

foreach ($marks as $mark) {
    echo $mark . " ";
}

echo "<br>Total Marks: " . $total;
echo "<br>Average Marks: " . $average;
echo "<br>Highest Marks: " . $highest;
echo "<br>Lowest Marks: " . $lowest;

?>
