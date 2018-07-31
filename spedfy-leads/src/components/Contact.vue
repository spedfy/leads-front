<template>
	<div class="container" id="spedfy-contact">
		<div class="jumbotron jumbotron-fluid">
			<div class="container">
				<header-contact></header-contact>
				<form-contact></form-contact>
				<footer-contact></footer-contact>
			</div>
		</div>			
	</div>
</template>

<script>
import HeaderContact from './HeaderContact'
import FormContact from './FormContact'
import FooterContact from './FooterContact'
	
export default {
	components: {
		HeaderContact, 
		FormContact,
		FooterContact
	},
	data() {
		return {
			name: '', 
			email: ''
		}
	}  
}
</script>

<style>
  #spedfy-contact {
    color: #fff;
  }
</style>