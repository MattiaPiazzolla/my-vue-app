<script>
export default {};
</script>
<template>
	<div class="jumbo">
		<p>Questo è il mio primo jumbotron con vue!</p>
	</div>
</template>
<style>
* {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}
body {
	font-family: sans-serif;
	background-color: rgba(0, 0, 0, 0.649);
}
.jumbo {
	width: 50%;
	min-height: 50vh;
	background-image: url("/Jumbotron.jpeg");
	background-size: cover;
	background-position: center;
	display: flex;
	justify-content: center;
	align-items: center;
	border-radius: 10px;
}
p {
	color: #fff;
	font-size: 2rem;
	transition: all 0.5s;
}
.jumbo:hover p {
	transform: scale(1.05);
}
</style>
