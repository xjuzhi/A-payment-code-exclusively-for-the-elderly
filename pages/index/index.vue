<template>
	<div>
		<div class="vxpay pay" v-if="changepay">
			<image src="/static/vx.jpg" alt="微信收款码"></image>
		</div>
		<div class="zfbpay pay" v-else>
			<image src="@/static/zfb.jpg" alt="支付宝收款码"></image>
		</div>
		<button @click="changeif">切换收款码</button>
	</div>
</template>

<script setup>
import { ref } from "vue";
const changepay = ref(true)
const changeif = () => {
	changepay.value = !changepay.value
}
</script>

<style>
.pay {
	height: 80vh;
}
image {
	display: initial;
	width: 100%;
	height: auto;
	text-align: center;
}
button {
	width: 100px;
	height: 50px;
}
</style>

