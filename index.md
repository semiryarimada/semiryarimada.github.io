<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" >
<head>
    <title></title>
<script type="text/javascript" src="http://code.jquery.com/jquery-1.11.0.min.js"></script>
<script type="text/javascript">
$(document).ready(function(){

    $('#button').click(function(e) {  
        var inputvalue = $("#input").val();
        window.location.replace(" https://www.sci-hub.do/"+inputvalue);

    });
});
</script> 
</head>
<body>

       <input type="text" value="11" id="input"> 
       <button type="button" id="button">Gönder</button>
</body>
</html>
