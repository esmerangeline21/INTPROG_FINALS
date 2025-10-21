<?php
$jsonString = '{"name":"Angeline","age":30,"email":"angeline@example.com"}';

$phpObject = json_decode($jsonString); "<br>";
$phpArray = json_decode($jsonString, true);"<br>";
echo "Object: Angeline";
"<br>";
echo "Array: angeline@gmail.com" . $phpArray['email']
