Here’s the direct PHP code examples for each conditional statement:

<?php
// if statement
$age = 20;
if ($age >= 18) {
    echo "You are allowed to vote.<br>";
}

// if...else statement
$temperature = 30;
if ($temperature > 25) {
    echo "It's a hot day.<br>";
} else {
    echo "It's a cool day.<br>";
}

// if...elseif...else statement
$grade = 85;
if ($grade >= 90) {
    echo "You got an A.<br>";
} elseif ($grade >= 80) {
    echo "You got a B.<br>";
} elseif ($grade >= 70) {
    echo "You got a C.<br>";
} else {
    echo "You need to improve.<br>";
}

// switch statement
$day = "Tuesday";
switch ($day) {
    case "Monday":
        echo "Start of the week.<br>";
        break;
    case "Tuesday":
        echo "Second day of the week.<br>";
        break;
    case "Friday":
        echo "Almost weekend!<br>";
        break;
    case "Sunday":
        echo "Rest day.<br>";
        break;
    default:
        echo "Just another day.<br>";
}
?>
