TUGAS-BESAR
===========
<?php
Session_start();
Session_register("count");
$count++;
?>
<html>
<head>
      <title> Demo Session 1 </title>
</head>
<body>
<h1> Demo Session 1 </h1>
<?
Echo "Anda telah mengakses halaman ini sebanyak : $count kali";
?>
</body>
</html>
