// 获取ID
function $(id){
	var _id=document.getElementById(id);
	return _id;
}

// 随机数
function Random(min,max){
	max++;
	var a=Math.floor(Math.random()*(max-min)+min);
	return a;
}
