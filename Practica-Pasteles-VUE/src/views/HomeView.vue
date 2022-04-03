<template>
  <div class="home">

    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
  </div>

	<div class="container-fluid">
			<div class="row">
				<div class="col-12 col-md-6">

				</div>

				<div class="col-12 col-md-6">
						<opiniones></opiniones>
				</div>
			</div>
	</div>

</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src
import opiniones from '@/components/opiniones.vue'; // @ is an alias to /src

import menu from '@/components/menu.vue'; // @ is an alias to /src

@Options({
  components: {
    HelloWorld,
    menu
    // eslint-disable-next-line no-undef

  },
})
export default class HomeView extends Vue {}
</script>
