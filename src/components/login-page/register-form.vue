<template id="main">
	<v-ons-page>

	<v-ons-toolbar>
		<div class="center">Register to Restourant App</div>
	</v-ons-toolbar>

	<v-ons-list>
		<v-ons-list-item>
			<div class="center">
				<v-ons-input placeholder="First name" float v-model="first_name">
				</v-ons-input>
			</div>
		</v-ons-list-item>

		<v-ons-list-item>
			<div class="center">
				<v-ons-input placeholder="Last name" float v-model="last_name">
				</v-ons-input>
			</div>
		</v-ons-list-item>

		<v-ons-list-item>
			<div class="center">
				<v-ons-input placeholder="Email" float v-model="email">
				</v-ons-input>
			</div>
		</v-ons-list-item>

		<v-ons-list-item>
			<div class="center">
				<v-ons-input placeholder="Password" float v-model="password">
				</v-ons-input>
			</div>
		</v-ons-list-item>

		<v-ons-list-item>
			<div class="center">
				<v-ons-input placeholder="Repeat password" float v-model="repeat_password">
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
			irst_name: '',
			last_name: '',
			email: '',
			password: '',
			repeat_password: ''
    }
	},

	metods: {
		//
	}
}
</script>
