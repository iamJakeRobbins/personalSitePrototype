<template lang="html">
	<div class="scrollContainer">
			<h2>we're going to test a scrolling banner here!</h2>
			<div id="container">
    <!-- Each image is 350px by 233px -->
    <div class="photobanner">
    	<img class="first" src="moonlit" alt="" />
    	<img src="../assets/images/alpine_alps.jpg" alt="" />
    	<img src="../assets/images/cabins.jpg" alt="" />
    	<img src="../assets/images/fingal_head.jpg" alt="" />
    	<img src="../assets/images/foggy.jpg" alt="" />
    	<img src="../assets/images/moon_mountain.jpg" alt="" />
			<img src="../assets/images/moonlit.jpg" alt="" />
			<img src="../assets/images/alpine_alps.jpg" alt="" />
    	<img src="../assets/images/cabins.jpg" alt="" />
    	<img src="../assets/images/fingal_head.jpg" alt="" />
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
	height: 233px;
	width: 350px;
}
#container {
 width: 1000px;
 overflow: hidden;
 margin: 50px auto;
 background: white;
}
.photobanner {
 height: 233px;
 width: 3550px;
 margin-bottom: 80px;
}
</style>
