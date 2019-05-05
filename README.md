<!DOCTYPE html>
<html>
<head lang="en">
    <meta charset="UTF-8">
    <title>首字母变大写</title>
</head>
<body>
<script>
   function capital(small){
        var arr=small.split(" "),
            a=" ";
        for(var i=0;i<arr.length;i++){
             a+=arr[i].charAt(0).toUpperCase()+arr[i].substr(1)+" ";
        }
        return a;
   }
   var result=capital("all time is no time when it is past");
   document.write(result);
</script>
</body>
</html>
