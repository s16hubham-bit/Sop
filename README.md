# Sop
IT codes 
<html>
<?php
// Display elements of an array along with their keys
$age = array("Ramesh"=>"51", "Rakesh"=>"32", "Rahul"=>"23");

foreach ($age as $x => $x_value)
{
    echo "Key = " . $x . ", Value = " . $x_value;
    echo "<br>";
}

// Display the size of an array
echo "<br>Size of Array is : " . count($age) . "<br>";

// Delete an element from an array from the given index
$data = array(1, 2, 3, 4, 5);

for ($i = 0; $i < count($data); $i++)
{
    echo " " . $data[$i];
}

unset($data[1]);

echo "<br>Elements After Deleting : <br>";

for ($i = 0; $i < count($data); $i++)
{
    echo " " . $data[$i];
}
?>
</html>



sop 4

<!doctype html>
<html>
<head>
    <title>Audio On A Webpage</title>
</head>
<body>
    <audio src="test.mp3" type="audio/mp3" autoplay>
    </audio>
</body>
</html>

<!doctype html>
<html>
<head>
    <title>Audio On A Webpage with multiple file formats</title>
</head>

<body>
    <audio controls autoplay>
        <source src="test.mp3" type="audio/mp3" controls muted>
        <source src="test.wav" type="audio/wav" controls muted>
        <source src="test.ogg" type="audio/ogg" controls muted>
    </audio>
</body>
</html>
