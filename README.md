# Demo
<html>
<body>

<form action="demo.php" method="post">
Name: <input type="text" name="name"><br>
<input type="submit">
</form>
</body>
</html>

<?php 

$name = $_POST['name'];

function display_input($name){
$number = rand(6,15);
echo "$name " . "$number";
}
display_input($name);
?>
