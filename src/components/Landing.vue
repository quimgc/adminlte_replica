<template>
  <div class="main">
	  <div class="title">
		  <h1><a href="https://github.com/quimgc">Quimgc</a> <a href="https://adminlte.io/">ADMINLTE</a> Replica</h1>
	  </div>
	  <div class="login center">
		  <button class="btn btn-login radius-25">LOGIN</button>
	  </div>
	<footer class="fixed-end">
		<div>
			<p><b>Created by:</b> <a href="https://github.com/quimgc">Quimgc</a></p>
			<p>All rights reserver</p>
		</div>
	</footer>
  </div>

</template>

<script>
export default {
  name: 'Landing',
  data () {
    return {
      msg: 'todo'
    }
  }
}
</script>

<style scoped>

	.main {
		font-family: Arial, Helvetica, sans-serif;
		display: flex;
		flex-direction: column;
		background-color: #DBDBDB;
		height: 100%;
		width: 100%;
	}

	.title {
		display: flex;
		align-items: center;
		flex-direction: column;
		text-align: center;
		justify-content: center;
	}

	.title h1 {
		font-size: 70px;
	}

	a {
		text-decoration: none;
		color: inherit;
	}

	.btn {
		padding: 50px;
		border: none;
		cursor: pointer;
		color: #373737;
		font-weight: bold;
		font-size: 30px;
	}

	.radius-25 {
		border-radius: 25%;
	}

	.login {
		margin-top: 2%;
	}

	.btn-login {
		background-color: #9C9B9B;
		box-shadow: 0 2px #999;
	}

	.btn-login:hover {
		background-color: #808080;
	}

	.center {
		display: flex;
		justify-content: center;
	}

	.fixed-end {
		
	}
</style>
