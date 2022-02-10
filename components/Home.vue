<!-- Please remove this file from your project -->
<template>
	<div class="home-page">
		<header class="home-page-header">
  		<div class="home-page-banner"></div>
			<div class="home-page-outer">
				<div class="home-page-title">
					<a href="/">呜呜呜</a>
				</div>
			</div>

		</header>

	</div>
</template>

<script>
export default {
  name: 'NuxtTutorial',
}
</script>
<style scoped>
.home-page .home-page-header{
	height: 300px;
	position: relative;
	border-bottom: 1px solid #ddd;
}
.home-page-banner{
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	background: url('/job/trs-web/ws/dist/banner.jpeg') center #000;
	-webkit-background-size: cover;
	-moz-background-size: cover;
	background-size: cover;
	z-index: -1;
}
.home-page-outer{
	height: 100%;
	position: relative;
}
.home-page-title{
	text-align: center;
	height: 40px;
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	width: 80%;
}
.home-page-title a {
	text-decoration: none;
	color: #fff;
	font-weight: 300;
	text-shadow: 0 1px 4px rgba(0, 0, 0, 0.3);
	font-size: 40px;
	line-height: 40px;
	letter-spacing: 2px;
}
</style>