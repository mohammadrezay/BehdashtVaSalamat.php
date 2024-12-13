# BehdashtVaSalamat.php
https://quera.org/problemset/51865?tab=description
<?php
$X = (int)readline("Enter your mark: ");
$N = (int)readline("Enter days: ");
$m = $X - $N;
if($N == 0){
	echo 20;
}elseif($N == 7){
	echo $X;
}else{
	if($m <= 0){
		echo 0;
	}else{
		echo $m;
	}
}
