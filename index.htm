<?PHP
$Address_Data = GetADD();//调用获取地点数据
if($Address_Data['country'] == '中国') $Address_Data['country']="";//如果国家是中国，则地名不显示中国。如果是其他国家则正常显示
if($Address_Data['province'] == $Address_Data['city'])$Address_Data['city']="";//如果省份和城市相同、则只显示一个
$User_Address = $Address_Data['country'].$Address_Data['province'].$Address_Data['city'];//将地区信息储存在$User_Address中
if(empty($Address_Data['ip'])){$Address_Data['ip'] = "您";$User_Address = "你那里";}//错误处理，加入获取不了IP的处理方式


function GetADD($ip = ''){  
    if(empty($ip)){  
        $ip =$_SERVER["REMOTE_ADDR"];  
    }  
    $res = @file_get_contents('http://int.dpool.sina.com.cn/iplookup/iplookup.php?format=js&ip=' . $ip); //经测试@file_get_contents可用，不必使用cURL 
    if(empty($res)){ return false; }  
    $jsonMatches = array();  
    preg_match('#\{.+?\}#', $res, $jsonMatches);  
    if(!isset($jsonMatches[0])){ return false; }  
    $json = json_decode($jsonMatches[0], true);  
    if(isset($json['ret']) && $json['ret'] == 1){  
        $json['ip'] = $ip;  
        unset($json['ret']);  
    }else{  
        return false;  
    }  
    return $json;  
}
?>

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xml:lang="en" xmlns="http://www.w3.org/1999/xhtml">
	<head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<title>祝阿里云越办越好</title>	    
		<script type="text/javascript" src="./aliyun/jquery.min.js"></script>
		<script type="text/javascript" src="./aliyun/jscex.min.js"></script>
		<script type="text/javascript" src="./aliyun/jscex-parser.js"></script>
		<script type="text/javascript" src="./aliyun/jscex-jit.js"></script>
		<script type="text/javascript" src="./aliyun/jscex-builderbase.m.js"></script>
		<script type="text/javascript" src="./aliyun/jscex-async.min.js"></script>
		<script type="text/javascript" src="./aliyun/jscex-async-powerpa.js"></script>
		<script type="text/javascript" src="./aliyun/functions.js" charset="utf-8"></script>
		<script type="text/javascript" src="./aliyun/love.js"></script>
		<link rel="stylesheet" href="./aliyun/main.css" type="text/css" />
	</head>
    <body>
		<audio autoplay="autopaly">
			<source src="./aliyun/bgm.js" type="audio/mp3">
		</audio>
        <div id="main">
            <div id="error">本页面采用HTML5，很遗憾你的浏览器不支持本页面，请换成其他浏览器，或者更新到最新版本。</div>
             <div id="wrap">
                <div id="text">
			        <div id="code">
						<font color="#FF0000">  	
						<span class="say">亲爱的用户:<br>&nbsp;您好!</span><br>
						<span class="say"> </span><br>
						<span class="say"> <b><?php echo $User_Address?></b>好玩吗？我一直想去，</span><br>
						<span class="say"> </span><br>
			        	<span class="say">可是，自从<B>2009年09月10号。</B></span><br>
						<span class="say"> </span><br>
						<span class="say">阿里云成立，</span><br>
						<span class="say">就必须无时无刻地为programmer服务。</span><br>
						<span class="say">我不能走开，一步也不可以。 </span><br>
						<span class="say">我的目的是，为大家提供优质的服务。 </span><br>
						<span class="say"> </span><br>
                        <span class="say"><span class="space"></span> -- 一个无名的Coder--</span><br>
                        <span class="say"></span><br><br>
                      	<span class="say">对<?php echo  $Address_Data['ip'] ?>表示最真挚的问候~~</span>
			  </font>
			  <p></p>
      </div>
                </div>
                <div id="clock-box">
                    <span class="STYLE1"></span><font color="#33CC00">亲爱的用户，阿里云</font>
					<span class="STYLE1">已经<font color="red">稳定</font>运营了</span>
                  <div id="clock"></div>
              </div>
                <canvas id="canvas" width="1100" height="680"></canvas>
            </div>
			<script type="text/javascript" src="./aliyun/main.js"></script>	
		</div>
	</body>
</html>