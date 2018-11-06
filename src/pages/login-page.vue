<template id="main">
<v-ons-page>
  <login-form></login-form>
  <!-- <register-form></register-form> -->
</v-ons-page>
</template>


<script>
import LoginForm from '../components/login-page/login-form';
import RegisterForm from '../components/login-page/register-form';

export default {
  data () {
    return {

    }
  },

  components: {
    LoginForm,
    RegisterForm
  }
}
</script>
