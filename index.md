<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>计算平方</title>
<script type="text/javascript">
//计算数字的平方
function cal()
{
	//获取文本框，从中取值

	var input=document.getElementById("num");
	//获取span向其写入值
	var span= document.getElementById("result");
	
    //获取文本框的值
    var n=input.value;
    //如果文本框中没有输入任何内容，则文本框中获取的值是“”

if(n==""||isNaN(n))
	{
	span.innerHTML ="请输入数字"
	}
else{
	
	span.innerHTML = n*n;
}
}
</script>

</head>
<body>
<input type="text" id="num"/>
<input type="button" value="平方" onclick="cal();"/>
=
<span id="result"></span>

</body>
</html>
