<template>
    <header>
        <div class="logos">
            <nuxt-link to="/" class="logo">Joel Krause</nuxt-link>
            <nuxt-link to="/" class="logo">Joel Krause</nuxt-link>
            <nuxt-link to="/" class="logo">Joel Krause</nuxt-link>
            <nuxt-link to="/" class="logo">Joel Krause</nuxt-link>
            <nuxt-link to="/" class="logo">Joel Krause</nuxt-link>
            <nuxt-link to="/" class="logo">Joel Krause</nuxt-link>
            <nuxt-link to="/" class="logo">Joel Krause</nuxt-link>
            <nuxt-link to="/" class="logo">Joel Krause</nuxt-link>
            <nuxt-link to="/" class="logo">Joel Krause</nuxt-link>
            <nuxt-link to="/" class="logo">Joel Krause</nuxt-link>
            <nuxt-link to="/" class="logo">Joel Krause</nuxt-link>
            <nuxt-link to="/" class="logo">Joel Krause</nuxt-link>
            <nuxt-link to="/" class="logo">Joel Krause</nuxt-link>
            <nuxt-link to="/" class="logo">Joel Krause</nuxt-link>
            <nuxt-link to="/" class="logo">Joel Krause</nuxt-link>
            <nuxt-link to="/" class="logo">Joel Krause</nuxt-link>
        </div>
    </header>
</template>

<style lang="scss" scoped>
header{
    display: flex;
    font-size: 3vw;
    padding: 2rem;
    white-space: nowrap;
    max-width: 100vw;
    overflow: hidden;
    align-items: center;
    height: 6vw;
    position: relative;
    .logos{
        animation-duration: 100s;
        animation-name: ticker;
        animation-timing-function: linear;
        animation-iteration-count: infinite;
        position: absolute;
    }
    .logo{
        text-transform: uppercase;
        color:#fff;
        text-decoration: none;
        padding: 0 2rem 0 0;
    }
	@-webkit-keyframes ticker {
	0% {
		-webkit-transform: translate3d(0, 0, 0);
		transform: translate3d(0, 0, 0);
		visibility: visible;
	}

	100% {
		-webkit-transform: translate3d(-100%, 0, 0);
		transform: translate3d(-100%, 0, 0);
	}
	}

	@keyframes ticker {
	0% {
		-webkit-transform: translate3d(0, 0, 0);
		transform: translate3d(0, 0, 0);
		visibility: visible;
	}

	100% {
		-webkit-transform: translate3d(-100%, 0, 0);
		transform: translate3d(-100%, 0, 0);
	}
	}
}
</style>