<template>
  <div>
    <section class="home">
      <h1>Quimgc ADMINLTE REPLICA</h1>
      <h2>LANDING PAGE</h2>
		<a class="btn btn-success" href="#/login">LOGIN</a>
    </section>

    <section class="description">
      <!--https://www.flaticon.com/packs/help-and-support?group_id=1-->

      <h3>Fucking marvelous!</h3>

    </section>

    <footer>
		<p>Còpia de Landing Page de l'ADMINLTE. Realitzat per <b><a target="_blank" href="https://www.github.com/quimgc">quimgc</a></b>.</p>
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

a {
  text-decoration: none;
  color: inherit;
}

div {
  background-color: #f2cc90;
  font-family: Arial, Helvetica, sans-serif;
  font-weight: 300;
  font-size: 16px;
  color: #4a0132;
}


h1, h2, h3, h4, h5, h6 {
  font-weight: 300;
  color: #333;
}

ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

.home {
  background-color: #35495f;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}

.home h1 {
  margin-top: 30px;
  margin-bottom: 20px;
  font-size: 70px;
  color: #fff;
}

.home h2{
  margin: 0;
  margin-bottom: 1em;
  font-size: 50px;
  color: #fff;
}

.home h1 {
  color: #c4aa6c;
  font-weight: 600;
}

.home a {
	padding: 40px;
	font-size: 40px;
}

.btn {
  border: 1px solid transparent;
  border-radius: 0.7em;
  padding: 1em;
  color: #fff;
  margin-bottom: 1em;
}


.btn-success {
  background-color: #b83217;
}

.btn-success:hover {
  background-color: #9d5237;
}

.home img {
  margin-bottom: 1em;
}

.description {
  display: flex;
  flex-direction: column;
  align-items: center;
	position:center;
	bottom:0px;
}

.description .features {
  display: flex;
}

.description_icon {
  height: 10em;
  width: 10em;
}
.description {

}
footer {
	border-radius: 10px;
	background-color: #222222;
	color: #fff;
	display: flex;
	justify-content: center;
	text-align: center;
	position:fixed;
	bottom:0px;
	width:100%;
}
footer a {
	text-decoration: underline  !important;
}

</style>
