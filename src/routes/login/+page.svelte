<script></script>
<svelte:head>
	<title>Kinde Auth | SvelteKit Starter Kit</title>
</svelte:head>

<body>
	<div class="screen-1">
		<svg
			class="logo"
			xmlns="http://www.w3.org/2000/svg"
			xmlns:xlink="http://www.w3.org/1999/xlink"
			version="1.1"
			width="300"
			height="300"
			viewbox="0 0 640 480"
			xml:space="preserve"
			><g transform="matrix(3.31 0 0 3.31 320.4 240.4)"
				><circle
					style="stroke: rgb(0,0,0); stroke-width: 0; stroke-dasharray: none; stroke-linecap: butt; stroke-dashoffset: 0; stroke-linejoin: miter; stroke-miterlimit: 4; fill: rgb(61,71,133); fill-rule: nonzero; opacity: 1;"
					cx="0"
					cy="0"
					r="40"
				/></g
			><g transform="matrix(0.98 0 0 0.98 268.7 213.7)"
				><circle
					style="stroke: rgb(0,0,0); stroke-width: 0; stroke-dasharray: none; stroke-linecap: butt; stroke-dashoffset: 0; stroke-linejoin: miter; stroke-miterlimit: 4; fill: rgb(255,255,255); fill-rule: nonzero; opacity: 1;"
					cx="0"
					cy="0"
					r="40"
				/></g
			><g transform="matrix(1.01 0 0 1.01 362.9 210.9)"
				><circle
					style="stroke: rgb(0,0,0); stroke-width: 0; stroke-dasharray: none; stroke-linecap: butt; stroke-dashoffset: 0; stroke-linejoin: miter; stroke-miterlimit: 4; fill: rgb(255,255,255); fill-rule: nonzero; opacity: 1;"
					cx="0"
					cy="0"
					r="40"
				/></g
			><g transform="matrix(0.92 0 0 0.92 318.5 286.5)"
				><circle
					style="stroke: rgb(0,0,0); stroke-width: 0; stroke-dasharray: none; stroke-linecap: butt; stroke-dashoffset: 0; stroke-linejoin: miter; stroke-miterlimit: 4; fill: rgb(255,255,255); fill-rule: nonzero; opacity: 1;"
					cx="0"
					cy="0"
					r="40"
				/></g
			><g transform="matrix(0.16 -0.12 0.49 0.66 290.57 243.57)"
				><polygon
					style="stroke: rgb(0,0,0); stroke-width: 0; stroke-dasharray: none; stroke-linecap: butt; stroke-dashoffset: 0; stroke-linejoin: miter; stroke-miterlimit: 4; fill: rgb(255,255,255); fill-rule: nonzero; opacity: 1;"
					points="-50,-50 -50,50 50,50 50,-50 "
				/></g
			><g transform="matrix(0.16 0.1 -0.44 0.69 342.03 248.34)"
				><polygon
					style="stroke: rgb(0,0,0); stroke-width: 0; stroke-dasharray: none; stroke-linecap: butt; stroke-dashoffset: 0; stroke-linejoin: miter; stroke-miterlimit: 4; fill: rgb(255,255,255); fill-rule: nonzero; opacity: 1;"
					vector-effect="non-scaling-stroke"
					points="-50,-50 -50,50 50,50 50,-50 "
				/></g
			></svg
		>
		<div class="email">
			<label for="email">Email Address</label>
			<div class="sec-2">
				<ion-icon name="mail-outline" /><input
					type="email"
					name="email"
					placeholder="Username@gmail.com"
				/>
			</div>
		</div>
		<div class="password">
			<label for="password">Password</label>
			<div class="sec-2">
				<ion-icon name="lock-closed-outline" /><input
					class="pas"
					type="password"
					name="password"
					placeholder="············"
				/>
				<ion-icon class="show-hide" name="eye-outline" />
			</div>
		</div>
		<button class="login">Login </button>
		<div class="footer"><span>Sign up</span><span>Forgot Password?</span></div>
	</div>
</body>
<style lang="scss">
	@import './style.scss';
  </style>
