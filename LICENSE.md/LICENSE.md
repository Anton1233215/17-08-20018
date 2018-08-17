<?php
$x = rand(0,100); 
$a = 1;
$b = 1;

echo "<p>Число $x</p>";

while ($a < $x) {
	$c = $a;
	$a = $a + $b;
	$b = $c;
	
	if ($a > $x) {
break;
}
}

if ($a > $x)
	echo "Не входит в числовой ряд";
else
	if ($a == $x)
		echo "Входит в числовой ряд";

?>
