<template>
<div class="main">
	<div class="content">
			<div class="column one">
				<h5 class="head">koimburi</h5>
				<div class="intro-words">
					<p class="title">Hello there,<br/>
						<span class="text_1">I'm koimburi.</span>
						<!-- <span class="text_2">I'm a web designer.</span> -->
						<span class="text_2">I'm a software developer.</span>
					</p>
					<p class="info"> Currently curating designs for new startups and founders. Also love coding in python and javascript.</p>

					<div class="button">projects</div>
				</div>
			</div>

			<div class="column two">
				<div class="menu">
					<div class="menu-bar-one"></div>
					<div class="menu-bar-two"></div>
					<div class="menu-bar-three"></div>
				</div>
			</div>

	</div>
</div>
</template>

<script type="text/javascript">
	// var i = 0;
	// var txt = ["I am koimburi", "I am a web designer", "I am a software developer"]
	// var speed = 50;

	// document.body.onload=function typeWriter(){
	// 	if(i< txt.length){
	// 		document.getElementById("typed").innerHTML+= txt.charAt(i);
	// 		i++;
	// 		setTimeout(typeWriter, speed);
	// 	}
	// txt.forEach(typeWriter);
		
	// }

</script>
<style >

	@import url('https://fonts.googleapis.com/css2?family=Luckiest+Guy&family=Permanent+Marker&family=Poppins:wght@300&display=swap');
	*{
		margin: 0;

	}
	.main{
		width: 100vw;
		height: 100vh;
		margin: 0;
		/*background-image: url("../../static/images/sky.jpg"); /* The image used */
		/*background-color: #cccccc;  
		background-position: center; 
		background-repeat: no-repeat; 
		background-size: cover; */
		background-color: #EEBED3;
		display: flex;
		justify-content: center;
		align-items: center;
  
	}
	.content{
		width: 85vw;
		height: 80vh;
		background-color: white;
		display: flex;
		border-radius: 35px;
		background-color: #EEBED3;


	
	}
	.head{
		font-family: 'Luckiest Guy', cursive;
		padding-left: 50px;
		padding-top: 50px;
		font-size: 22px;
		color:  black;

	}
	.intro-words{
		width: 350px;
		margin:0 auto;
		font-family: 'Poppins', sans-serif;
		margin-top: 80px;
		text-align: center;
	}
	.title{
		font-weight: bold;
		font-size: 26px;
	}
	.info{
		padding-top: 40px;
		padding-bottom: 40px;
		color: grey;
		font-size: 17px;
	}
	.column{
		flex:50%;
	}

	.button{
		width: 130px;
		text-align: center;
		height: 45px;
		background-color: #EEBED3;
		margin: 0 auto;
		padding-top: 16px;
		font-size: 20px;

	}
	.one{
		background-color: white;
		border-top-left-radius: 35px;
		border-bottom-left-radius: 35px;

	}
	.two{
		background-image: url("../../static/images/abst.png"); /* The image used */
		background-color: white;  
		background-repeat: no-repeat; 
		background-size: 100% 80%;
		background-position: bottom;
		border-top-right-radius: 35px;
		border-bottom-right-radius: 35px;
	}
	.menu{
		float: right;
		padding-top: 50px;
		padding-right: 50px;
	}
	.menu-bar-one{
		width: 25px;
		margin-bottom: 5px;

		border-bottom: 2px black solid;
	}
	.menu-bar-two{
		width: 25px;
		margin-bottom: 5px;

		border-bottom: 2px black solid;
	}
	.menu-bar-three{
		width: 25px;
		margin-bottom: 5px;
		border-bottom: 2px black solid;
	}
	.text_1 {
		animation: text1;
			}
	.text_2 {
		animation: text2;
	}	
	.text_1, .text_2 {
		overflow: hidden;
		white-space: nowrap;
		display: inline-block;
		position: relative;
		animation-duration: 12s;
		animation-timing-function: steps(15, end);
		animation-iteration-count: infinite;
		}	
	.text_1::after, .text_2::after {
		content: "|";
		position: absolute;
		right: 0;
		animation: caret infinite;
		animation-duration: 1s;
		animation-timing-function: steps(1, end);
		}
	@keyframes typewriter {
		0%, 100% {
			width: 0;
		}
		20%, 80% {
			width: 10.2em;
		}
	}
	@keyframes caret {
		0%, 100% {
			opacity: 0;
		}
		50% {
			opacity: 1;
		}
	}
	@keyframes text2 {
		0%, 50%, 100% {
			width: 0;
		}
		60%, 90% {
			width: 13em;
		}
	}
	@keyframes text1 {
		0%, 50%, 100% {
			width: 0;
		}
		10%, 40% {
			width: 7em;
		}
	}
	
</style>