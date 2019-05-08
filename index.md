<style>
    .smaller-image {
        width: 300px;
    }
    
    .bigger-image {
        width: 400px;
    }
    
    .smallest-image {
        width: 50px;
    }
    
    .image-position {
        width: 10px:
    }
    
    body {
        background-color: #CCFF99;
    }
    
    td {
        font-family: "微軟正黑體";
        font-size: 18px;
    }
    
    th {
        font-family: "微軟正黑體";
        font-size: 18px;
        font-weight: 900;
    }
    .circle-container {
	    position: relative;
	    /* 1 */
	    width: 20em;
	    height: 20em;
	    padding: 0;
	    border-radius: 50%;
	    list-style: none;
	    /* 2 */
	    box-sizing: content-box;
	    /* 3 */
	    margin: 5em auto 0;
	    border: solid 5px tomato;
	}

	.circle-container > * {
	    /* 4 */
	    display: block;
	    position: absolute;
	    top: 50%;
	    left: 50%;
	    width: 6em;
	    height: 6em;
	    margin: -3em;
	}

	.circle-container >:nth-of-type(1) {
	    transform: rotate(0deg) translate(10em) rotate(0deg);
	}

	.circle-container >:nth-of-type(2) {
	    transform: rotate(45deg) translate(10em) rotate(-45deg);
	}

	.circle-container >:nth-of-type(3) {
	    transform: rotate(90deg) translate(10em) rotate(-90deg);
	}

	.circle-container >:nth-of-type(4) {
	    transform: rotate(135deg) translate(10em) rotate(-135deg);
	}

	.circle-container >:nth-of-type(5) {
	    transform: rotate(180deg) translate(10em) rotate(-180deg);
	}

	.circle-container >:nth-of-type(6) {
	    transform: rotate(225deg) translate(10em) rotate(-225deg);
	}

	.circle-container >:nth-of-type(7) {
	    transform: rotate(270deg) translate(10em) rotate(-270deg);
	}

	.circle-container >:nth-of-type(8) {
	    transform: rotate(315deg) translate(10em) rotate(-315deg);
	}

	.circle-container img {
	    display: block;
	    width: 100%;
	    border-radius: 50%;
	    filter: grayscale(100%);
	}

	.circle-container img:hover {
	    filter: grayscale(0);
	}

</style>

<html>

<head>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
    <script>
        $(document).ready(function() {
            $('#top').click(function() {
                $('html, body').animate({
                    scrollTop: 0
                }, 1000);
            });
            $('#bottom').click(function() {
                $('html, body').animate({
                    scrollTop: $(document).height() - $(window).height()
                }, 1000);
            });
            $('#a').click(function() {
                $('html, body').animate({
                    scrollTop: $("#A").offset().top
                }, 1000);
            });
            $('#b').click(function() {
                $('html, body').animate({
                    scrollTop: $("#B").offset().top
                }, 1000);
            });
            $('#c').click(function() {
                $('html, body').animate({
                    scrollTop: $("#C").offset().top
                }, 1000);
            });
            $('#d').click(function() {
                $('html, body').animate({
                    scrollTop: $("#D").offset().top
                }, 1000);
            });
            $('#e').click(function() {
                $('html, body').animate({
                    scrollTop: $("#E").offset().top
                }, 1000);
            });
        });
    </script>
    
</head>

<body>
    <div style="font-family:微軟正黑體">
        <h1 style="color: black; font-weight: bold;font-size:40px"><center>台江國家公園</center></h1>

        <h1 style="color: black; font-weight: bold;font-size:0.8cm" id="A">基本資訊</h1>
        <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;font-size:18px;">
            <img style="width:300px;height:300px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/86/Yanshuei_River_marine_outfall.JPG/375px-Yanshuei_River_marine_outfall.JPG" align="right"> 台江國家公園是臺灣第8座國家公園，也是臺灣唯一濕地型國家公園。位於河海匯流之地，薈萃了「自然生態」、「人文歷史」與「漁鹽產業」等三大資源特色。廣大的河口、潟湖、魚塭及紅樹林等豐美的濕地環境，孕育了豐饒的生態資源，秋冬時節，也是候鳥過境、度冬的良好棲所；內海滄桑之變與開臺歷史，見證了台江地區深厚的文化底蘊；而阡陌縱橫的魚塭與鹽田，交織出人類與自然環境的和諧互動。台江國家公園宛若是一間間的戶外大教室，也是一所可以親近自然學習的濕地學校。 為透過環境教育服務，引領社會大眾及學校師生深度感受豐富的濕地生命，喚醒濕地保育意識與行動，台管處創設「台江濕地學校」，作為環境教育服務品牌。以多元且寓教於樂的課程，體驗台江獨特的資源特色，落實環境教育與永續發展之理念。 台江國家公園於2012年11月取得環保署環境教育設施場所認證，2013年「台江濕地學校」學習中心開放受理預約。2015年榮獲第三屆「國家環境教育獎」機關組優等獎，同年通過環保署評鑑並獲表揚為「優異環境教育設施場所場」，2017年取得國內第一個環境教育服務類「濕地標章」之肯定。
        </div>

        <h1 style="color: black; font-weight: bold;font-size:0.8cm" id="B">國家公園標誌意涵</h1>
        <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;font-size:18px;font-family:微軟正黑體">

            <p><img style="width:100px;height:100px" src="http://np.cpami.gov.tw/filesys/image/01_chinese/04_news/8logo.jpg" align="left"> 以河口、黑面琵鷺加上台灣船、鲲鯓（沙洲）為設計元素，表現陸域資源特色及台江先民勇渡黑 水溝（台灣海峽）墾拓顯著歷史，象徵台江國家公園的使命與目標。色彩上以「綠色」表現自然 生態生生不息，「藍色」寓意海洋生態資源豐沛之意象，整體造形既傳達台灣歷史足跡。
            </p>

        </div>

        <h1 style="color: black; font-weight: bold;font-size:0.8cm" id="C">公園特色介紹</h1>

        <h2>一、濕地 :</h2>
        <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
            <p><img style="width:300px;height:300px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/10/Salt_Mountain.jpg/275px-Salt_Mountain.jpg" align="left">
                <h3 style="font-size:18px;font-family:微軟正黑體;font-weight:900;">2007年中華民國內政部營建署評選75處國家級、國際級濕地，其中4處位於台江國家公園內。</h3>
                <h4 style="font-size:18px;font-family:微軟正黑體"><gg style="font-weight:900;">曾文溪口濕地：</gg>國際級，瀕臨絕種的黑面琵鷺每年有三分之二在此渡冬。</h4>
                <h4 style="font-size:18px;font-family:微軟正黑體"><gg style="font-weight:900;">四草濕地：</gg>國際級，範圍內有多處魚塭、鹽田、渠道及紅樹林，為高蹺鴴等水鳥繁殖與保護區。</h4>
                <h4 style="font-size:18px;font-family:微軟正黑體"><gg style="font-weight:900;">七股鹽田濕地：</gg>國家級，冬季吸引雁鴨，亦為黑面琵鷺棲息地。</h4>
                <h4 style="font-size:18px;font-family:微軟正黑體"><gg style="font-weight:900;">鹽水溪口濕地：</gg>國家級，有藻類、紅樹林等。</h4>
            </p>
        </div>

        <h2>二、河口沙洲潟湖生態 : </h2>
        <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
            <h3 style="font-size:18px;font-family:微軟正黑體"><gg style="font-weight:900;">海灘：</gg>因為波浪或沿岸流等搬運沙礫堆積在海濱，就形成了海灘。可分為沙灘、礫灘。</h3>
            <h3 style="font-size:18px;font-family:微軟正黑體"><gg style="font-weight:900;">沙洲：</gg>海中的沙礫，因波浪和海流的作用，在濱海地區形成的堤狀沙礫堆積地形，通稱沙洲或障沙島。沙洲完全不與海岸相連者，即為濱外沙洲或離岸沙洲。沙洲為地理學上的名詞，當地人則稱之為「汕」，如：新浮崙汕、頂頭額汕。</h3>
            <h3 style="font-size:18px;font-family:微軟正黑體"><gg style="font-weight:900;">沙嘴：</gg>沙洲的一端與陸地連接，另一端伸向海洋，稱為沙嘴，又稱為「汕尾」。</h3>
            <h3 style="font-size:18px;font-family:微軟正黑體"><gg style="font-weight:900;">潟湖：</gg>濱外沙洲與陸地之間所圍的水域。</h3>
            <h3 style="font-size:18px;font-family:微軟正黑體"><gg style="font-weight:900;">海埔地：</gg>即海埔新生地，係指在海岸地區經自然沈積或施工築堤涸出之土地，廣義而言，泛指臨海地區淺灘處表露的新生土地。</h3>
        </div>

        <h2>三、紅樹林濕地生態 : </h2>
        <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;font-size:18px;font-family:微軟正黑體">
            <h3><gg style="font-weight:900;">曾文溪北岸的紅樹林，以七股溪與三股溪會合口有近10公頃海茄苳純林的「海寮紅樹林保護區」最具代表性，不但林相優美，也是上千小白鷺、夜鷺及黃頭鷺的群聚營巢所在。 曾文溪北岸以南有三處可欣賞紅樹林濕地</gg></h3>
            <h3><gg style="font-weight:900;">1.</gg>在竹筏港潮溝及蔡姑娘廟附近水道，組成樹種為海茄苳及欖李。</h3>
            <h3><gg style="font-weight:900;">2.</gg>在四草地區大眾廟後面及東側水道的紅海欖（五梨跤）具茂密支持根及樹冠層，廟旁水道的海茄苳根據年輪調查應有超過數十年的歷史，形成獨特風格的「綠色隧道」。廟的前潮池及周邊水道有生長良好的欖李，六月開滿白花有如六月雪，另有少數人工復育的水筆仔，在此處小小範圍內可同時看到四種紅樹林植物。</h3>
            <h3><gg style="font-weight:900;">3.</gg>在四草湖區域（鹽水溪、嘉南大圳、運鹽古運河，與竹筏港溪交會處）有原生較大面積的海茄苳、欖李與紅海欖（五梨跤）的混合林。</h3>
        </div>
        <h2>四、沙洲 : </h2>
        <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;font-size:18px;font-family:微軟正黑體">
            <h3>曾文溪口離岸沙洲  臺南城西濱海沙洲  新浮崙汕</h3>
            <h3>青山港汕         網仔寮  頂頭額汕</h3>
        </div>
        <h2>五、古蹟與史蹟 : </h2>
        <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;font-size:18px;font-family:微軟正黑體">
            <h3>四草砲台(國定二級古蹟)      鹿耳門港</h3>
            <h3>安順鹽場運鹽碼頭(市定古蹟)  竹筏港</h3>
        </div>

        <h1 style="color: black; font-weight: bold;font-size:0.8cm" id="D">交通資訊</h1>
        <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
            <h3>♦ 搭乘高鐵：請至高鐵臺南站下車</h3>

            <h3>1. 轉乘高鐵接駁車高鐵臺南站－臺南市政府線：</h3>

            <h3>&nbsp;&nbsp;&nbsp;&nbsp;(1)至興南客運台南站下車，轉乘臺灣好行99台江線至四草大橋西站下車。</h3>

            <h3>&nbsp;&nbsp;&nbsp;&nbsp;(2)至臺南市政府站下車，轉搭計程車至台江國家公園管理處。</h3>

            <h3>2. 轉乘臺鐵沙崙線至臺南火車站，轉乘臺灣好行99台江線至四草大橋西站下車。</h3>

            <h3>♦  搭乘臺鐵：請至臺南站下車</h3>

            <h3>1. 轉乘臺灣好行99台江線至四草大橋西站下車。</h3>

            <h3>2. 轉乘計程車至台江國家公園管理處。</h3>
        </div>

        <h1 style="color: black; font-weight: bold;font-size:0.8cm" id="E">住宿資訊</h1>
        <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
            <p>
                <table border="1" cellpadding="5" cellspacing="0" width="90%">

                    <thead>
                        <tr>
                            <th width="31%">酒店/旅館 </th>
                            <th width="48%">地址</th>
                            <th width="18%">電話</th>
                        </tr>
                    </thead>

                    <tbody>

                        <tr>
                            <td>台南大員皇冠假日酒店</td>
                            <td>台灣台南安平區州平路289號</td>
                            <td>06-3911899</td>
                        </tr>

                        <tr>
                            <td>臺邦商旅</td>
                            <td>台灣台南安平區永華二街199號</td>
                            <td>06-2931888</td>
                        </tr>

                        <tr>
                            <td>沐府海旅</td>
                            <td>台灣台南安平區安億路288號</td>
                            <td> 06-2939998</td>
                        </tr>

                        <tr>
                            <td>歐薇汽車旅館(台南館)</td>
                            <td>台灣台南育平路181號</td>
                            <td>06-2993000</td>
                        </tr>

                        <tr>
                            <td>康橋商旅(臺南民生館)</td>
                            <td>台灣台南中西區民生路二段299號</td>
                            <td>06-2245566</td>
                        </tr>

                    </tbody>
                </table>
            </p>
        </div>

        <h1 style="color: black; font-weight: bold;font-size:0.8cm">美食資訊</h1>
        <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
            <p>
                <table border="1" cellpadding="5" cellspacing="0" width="90%">

                    <thead>
                        <tr>
                            <th width="31%">店名</th>
                            <th width="48%">地址</th>
                            <th width="18%">電話</th>
                        </tr>
                    </thead>

                    <tbody>

                        <tr>
                            <td>同記安平豆花</td>
                            <td>安平區安北路433號</td>
                            <td>0963915385</td>
                        </tr>

                        <tr>
                            <td>椰庭</td>
                            <td>四草大道261號四草里</td>
                            <td>0962840988</td>
                        </tr>

                        <tr>
                            <td>元素</td>
                            <td>州平路289號1樓</td>
                            <td>0963911899</td>
                        </tr>

                        <tr>
                            <td>文章牛肉湯</td>
                            <td>安平區安平路590號</td>
                            <td>0962284626</td>
                        </tr>

                        <tr>
                            <td>義豐冬瓜茶</td>
                            <td>安平區安平路768號</td>
                            <td>0962219197</td>
                        </tr>

                    </tbody>
                </table>
            </p>
        </div>

        <h1 style="color: black; font-weight: bold;font-size:0.8cm">參考資料</h1>
        <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
            <a href="https://www.tripadvisor.com.tw/RestaurantsNear-g13792454-d5513252-Taijian_National_Park-Annan_Tainan.html"><h3>貓途鷹(美食)</h3></a>
            <a href="https://www.tripadvisor.com.tw/HotelsNear-g13792454-d5513252-Taijian_National_Park-Annan_Tainan.html"><h3>貓途鷹(住宿)</h3></a>
            <a href="https://zh.wikipedia.org/wiki/%E5%8F%B0%E6%B1%9F%E5%9C%8B%E5%AE%B6%E5%85%AC%E5%9C%92"><h3>維基百科</h3></a>
            <a href="http://np.cpami.gov.tw/youth/index.php?option=com_content&view=article&id=4206&Itemid=6"><h3>台灣國家公園(公園標誌意涵)</h3></a>
            <a href="https://www.tjnp.gov.tw//chtNature/Environment/ShiDiXueXiao2.htm"><h3>台江國家公園(台江濕地學校)</h3></a>
        </div>
    </div>

    <ul class='circle-container'>
  		<li><img id="top" src='http://lorempixel.com/100/100/city'></li>
  		<li><img id="bottom" src='http://lorempixel.com/100/100/nature'></li>
  		<li><img id="a" src='http://lorempixel.com/100/100/abstract'></li>
  		<li><img id="b" src='http://lorempixel.com/100/100/cats'></li>
  		<li><img id="c" src='http://lorempixel.com/100/100/food'></li>
  		<li><img id="d" src='http://lorempixel.com/100/100/animals'></li>
  		<li><img id="e" src='http://lorempixel.com/100/100/business'></li>
  		<li><img src='http://lorempixel.com/100/100/people'></li>
	</ul>
</body>

</html>
