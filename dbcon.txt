<?php
$servername = "172.16.1.66";
$username = "root";
$password = "GfdbLocal@dmin123";

// Create connection
$conn = new mysqli($servername, $username, $password);

// Check connection
if ($conn->connect_error) {
  die("Connection failed: " . $conn->connect_error);
}
echo "Connected successfully";
?>