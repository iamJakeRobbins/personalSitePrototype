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

1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
40
41
42
43
44
45
46
47
48
49
50
51
52
53
54
55
56
57
58
/*keyframe animations*/
.first {
 -webkit-animation: bannermove 30s linear infinite;
    -moz-animation: bannermove 30s linear infinite;
     -ms-animation: bannermove 30s linear infinite;
      -o-animation: bannermove 30s linear infinite;
         animation: bannermove 30s linear infinite;
}

@keyframes "bannermove" {
 0% {
    margin-left: 0px;
 }
 100% {
    margin-left: -2125px;
 }

}

@-moz-keyframes bannermove {
 0% {
   margin-left: 0px;
 }
 100% {
   margin-left: -2125px;
 }

}

@-webkit-keyframes "bannermove" {
 0% {
   margin-left: 0px;
 }
 100% {
   margin-left: -2125px;
 }

}

@-ms-keyframes "bannermove" {
 0% {
   margin-left: 0px;
 }
 100% {
   margin-left: -2125px;
 }

}

@-o-keyframes "bannermove" {
 0% {
   margin-left: 0px;
 }
 100% {
   margin-left: -2125px;
 }

}
</style>
