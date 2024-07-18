
<?php 
/*

### task -1 
$N = 5; 
for ($i=0; $i<=$N ; $i++) { 
    echo $i;
}

#########################
### task -2

$N = 20;
for ($i=0; $i<=$N ; $i++) {
    if ($i % 2==0 ) {
        echo $i;
    }
}

######################
task -3

$numbers =[ 3,5,9,1,3 ];

        $maxNumber = max($numbers);
        echo "   اكبر عدد هو ال  :    "  ,$maxNumber  ;
        echo "<br>";

########################
### task -4


function isPrime($number) {
    if ($number <= 1) {
        return false;
    }
    if ($number == 2) {
        return true;
    }
    if ($number % 2 == 0) {
        return false;
    }
    for ($i = 3; $i * $i <= $number; $i += 2) {
        if ($number % $i == 0) {
            return false;
        }
    }
    return true;
}


$handle = fopen("php://stdin", "r");
$input = trim(fgets($handle));
fclose($handle);


$X = intval($input);


if (isPrime($X)) {
    echo "YES\n";
} else {
    echo "NO\n";
}

 
#######################
### task -5 



function processNumber($N) {
    // Convert the number to a string
    $strN = strval($N);

    // Reverse the string and remove leading zeroes
    $reversedStrN = ltrim(strrev($strN), '0');
    
    // Print the reversed number
    echo $reversedStrN . "\n";
    
    // Check if the original number is a palindrome
    $isPalindrome = ($strN === strrev($strN)) ? "YES" : "NO";
    
    // Print if the number is a palindrome
    echo $isPalindrome . "\n";
}

/// Example usage /// 
$N = 00321;  // Change this to any number you want to test
processNumber($N);


#######################\
### task -6


function myfunction ($n){
    $array = [];
    for ($i = 1; $i <= $n; $i++) {
        if ($n % $i ==0) {
            # code...
        echo $array[] = $i , "<br>";

        }
    }
}
myfunction(7)

*/
#######################\
### task -7




 




?>
