<template>
  <div class="main">
	  <div class="title">
		  <h1><a class="link-hover" href="https://github.com/quimgc">Quimgc</a> <a class="link-hover" href="https://adminlte.io/">ADMINLTE</a> Replica</h1>
	  </div>
	  <div class="login center">
		  <a class="btn btn-login radius-25" href="#/login">LOGIN</a>
	  </div>
	<footer class="fixed-end">
		<p><b>Created by:</b> <a class="link-hover" href="https://github.com/quimgc">Quimgc</a></p>
		<p> &copy;	2018</p>
		<p>All rights reserved</p>
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

	.link-hover:hover {
		color: #887F7F;
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

	footer {
		display: flex;
		background-color: #222222;
		color: #fff;
		justify-content: space-around;
		text-align: center;
	}

	.fixed-end {
		position:fixed;
		bottom:0px;
		width:100%;
	}
</style>
