<?php
header('Content-Type: application/json');
$userProfile = array(
    "id" => 1,
    "name" => "Angeline",
    "email" => "angeline@example.com",
    "status" => "active"
);

echo json_encode($userProfile);

?>
