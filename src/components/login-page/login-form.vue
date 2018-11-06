<template id="main">
	<v-ons-page>

	<v-ons-toolbar>
		<div class="center">Login to Restourant App</div>
	</v-ons-toolbar>

	<v-ons-list>
		<v-ons-list-item>
		<div class="center">
			<v-ons-input placeholder="Input your email" float v-model="email">
			</v-ons-input>
		</div>
		</v-ons-list-item>
		<v-ons-list-item>
		<div class="center">
			<v-ons-input placeholder="Input your password" float v-model="password">
			</v-ons-input>
		</div>
		</v-ons-list-item>
	</v-ons-list>

	<section style="margin: 16px">
		<v-ons-button style="margin: 6px 0">Login</v-ons-button>
		<v-ons-button style="margin: 6px 0">Sign Up</v-ons-button>
	</section>

	</v-ons-page>
</template>


<script>
export default {
  data() {
    return {
			email: '',
			password: ''
    }
	},

	metods: {
		//
	}
}
</script>
