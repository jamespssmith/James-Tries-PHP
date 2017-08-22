## Week Three - Loops

![ImageAltText](assets/images/3.jpg)



Activities
------ 


* Create a script that displays 1-2-3-4-5-6-7-8-9-10 on one line. There will be no hyphen(-) at starting and ending position.

```markdown

<html>

<head>
</head>

<body>

<?php
for($x=1; $x<=10; $x++)
{
 if($x< 10)
 {
 echo "$x-";
 }
 else
  {
 echo "$x"."\n";
  }
}
?>

</body>

</html>

```




* Create a script using a for loop to add all the integers between 0 and 30 and display the total.



```markdown

<html>
<head>
</head>
<body>

<?php
$sum = 0;
for($x=1; $x<=30; $x++)
{
$sum +=$x;
}
echo "The sum of the numbers 0 to 30 is $sum"."\n";
?>

</body>

</html>

```


* Write a PHP program which iterates the integers from 1 to 50. For multiples of three print "Fizz" instead of the number and for the multiples of five print "Buzz". For numbers which are multiples of both three and five print "FizzBuzz"



```markdown

<html>
<head>
</head>
<body>

<?php
for ($i = 1; $i <= 100; $i++)
{
  if ( $i%3 == 0 && $i%5 == 0 )
   {
     echo $i . " FizzBuzz"."\n" ;
   }
  else if ( $i%3 == 0 ) 
   {
     echo $i. " Fizz"."\n";
   }
     else if ( $i%5 == 0 ) 
   {
     echo $i. " Buzz"."\n";
   }
     else
   {
     echo $i."\n";
   }
 }
?>

</body>

</html>

```

### Download files:
Right click on links to save as single-files.


<a href="https://raw.githubusercontent.com/jamespssmith/James-Tries-PHP/master/activities/activity3-1.php">3-1</a>

<a href="https://raw.githubusercontent.com/jamespssmith/James-Tries-PHP/master/activities/activity3-2.php">3-2</a>

<a href="https://raw.githubusercontent.com/jamespssmith/James-Tries-PHP/master/activities/activity3-3.php">3-3</a>
