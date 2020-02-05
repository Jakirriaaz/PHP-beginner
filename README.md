# PHP-beginner==

# ==OPERATOR==

<?php

	//Arithmetic operator [+,-,*,/,%]
	
	
	$father =61;
	$son = 30;
	
	$total = $father % $son;
	
	echo $total;
	
	
	//assingment operator [+=,-=,*=,/=,%=]
	
	$age = 30;
	
	$age -=10;
	
	echo $age;
	
	//Logical operator [||, &&, !]
	
	$username = 'riaaz';
	$pass ='riaaz76';
	
	if ($username == 'riaaz' && $pass == 'riaaz76') {
		echo 'Welcome';
	}
	else {
		echo 'user or password wrong';
	}
	
	//Comparison operator [==,!=,>,>=,<,<=]
	
	$riaaz = 24;
	$imran = 24;
	
	if ($riaaz >= $imran) {
		echo 'true';
	}
	else {
		echo 'false';
	}
		
?>
