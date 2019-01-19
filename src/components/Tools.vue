<template lang="html">
	<div class="scrollContainer">
		<div id="container">
	    <div class="photobanner">
	    	<img class="first" src="../assets/images/Html.png" alt="" />
	    	<img src="../assets/images/Css.png" alt="" />
	    	<img src="../assets/images/Javascript.png" alt="" />
	    	<img src="../assets/images/Typescript.png" alt="" />
	    	<img src="../assets/images/Jquery.png" alt="" />
	    	<img src="../assets/images/Vue.png" alt="" />
				<img src="../assets/images/React.png" alt="" />
	    </div>
		</div>
	</div>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>
img{
	height: 128px;
	width: 128;
	padding: 5px;
}
#container {
 width: 1000px;
 overflow: hidden;
 margin: 50px auto;
}
header {
 width: 800px;
 margin: 40px auto;
}

header h1 {
 text-align: center;
 font: 100 60px/1.5 Helvetica, Verdana, sans-serif;

}

header p {
 font: 100 15px/1.5 Helvetica, Verdana, sans-serif;
 text-align: justify;
}

/*photobanner*/

.photobanner {
 height: 233px;
 width: 2000px;
 margin-bottom: 80px;
}

/*keyframe animations*/
.first {
 -webkit-animation: bannermove 10s linear infinite;
    -moz-animation: bannermove 10s linear infinite;
     -ms-animation: bannermove 10s linear infinite;
      -o-animation: bannermove 10s linear infinite;
         animation: bannermove 10s linear infinite;
}

@keyframes bannermove {
 0% {
    margin-left: 0px;
 }
 100% {
    margin-left: -1000px;
 }

}

@-moz-keyframes bannermove {
 0% {
   margin-left: 0px;
 }
 100% {
   margin-left: -1000px;
 }

}

@-webkit-keyframes "bannermove" {
 0% {
   margin-left: 0px;
 }
 100% {
   margin-left: -1000px;
 }

}

@-ms-keyframes "bannermove" {
 0% {
   margin-left: 0px;
 }
 100% {
   margin-left: -1000px;
 }

}

@-o-keyframes "bannermove" {
 0% {
   margin-left: 0px;
 }
 100% {
   margin-left: -1000px;
 }

}

.photobanner img {
 -webkit-transition: all 0.5s ease;
 -moz-transition: all 0.5s ease;
 -o-transition: all 0.5s ease;
 -ms-transition: all 0.5s ease;
 transition: all 0.5s ease;
}

.photobanner img:hover {
 -webkit-transform: scale(1.1);
 -moz-transform: scale(1.1);
 -o-transform: scale(1.1);
 -ms-transform: scale(1.1);
 transform: scale(1.1);
 cursor: pointer;

 -webkit-box-shadow: 0px 3px 5px rgba(0,0,0,0.2);
 -moz-box-shadow: 0px 3px 5px rgba(0,0,0,0.2);
 box-shadow: 0px 3px 5px rgba(0,0,0,0.2);
}
</style>
