<template>
	<div id="root">
		<div class="navbar navbar-default">
			<div class="navbar-brand">
				<router-link to="/">Brand Name</router-link>
			</div>

			<div class="nav navbar-nav navbar-left">
				<li><router-link to="/">Customer</router-link></li>
				<li><router-link to="/invoice">Invoice</router-link></li>
			</div>
		</div>
		<router-view></router-view>
	</div>
</template>