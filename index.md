<html>

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

    <ul class='circle-container'>
  		<li><img id="top" src='http://lorempixel.com/100/100/city'></li>
  		<li><img id="bottom" src='http://lorempixel.com/100/100/nature'></li>
  		<li><a href=" https://gary7lu.github.io/Kinmen-National-Park/" target="_blank"><img id="a" src='https://upload.wikimedia.org/wikipedia/zh/thumb/b/ba/Suneo.png/220px-Suneo.png'></a></li>
  		<li><img id="b" src='https://www.itsfun.com.tw/cacheimg/ef/da/3e83ab30ecb07bec35a97634d136.jpg'></li>
  		<li><a href=" https://kaidung.github.io/Yushan-National-Park/" target="_blank"><img id="c" src='https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/cov328n38-1556448371.jpg?crop=0.330xw:0.658xh;0.670xw,0&resize=640:*'></a></li>
  		<li><a href="https://kaidung.github.io/Dongsha-Atoll-National-Park/" target="_blank"><img id="d" src='https://jibaofiles.s3.amazonaws.com/import-images/5a0c056ee676ff25761f086a.jpg'></a></li>
  		<li><img id="e" src='http://lorempixel.com/100/100/business'></li>
  		<li><img src='http://lorempixel.com/100/100/people'></li>
	</ul>
</body>

</html>
