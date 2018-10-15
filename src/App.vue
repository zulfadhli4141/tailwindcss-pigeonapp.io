<template>
  <div id="app" class="font-sans antialiased leading-tight text-grey-darkest bg-grey-lighter">
    <header class="relative min-h-screen bg-white">
      <div class="absolute w-full h-full bg-no-repeat bg-top pin-y" :style="'backgroundImage: url('+bgImage+')'" style="background-position-x: 75%;">
        <div class="container mx-auto p-24">
          <div class="flex justify-end mb-24">
            <a href="#" class="text-black font-bold hover:text-pigeon-orange bg-white px-6 py-4 rounded shadow">PRIVATE BETA</a>
          </div>
          <div class="flex">
            <div class="w-full lg:w-1/2">
              <figure class="mb-12">
                <img src="./assets/pigeon.png" alt="">
            </figure>
                <h1 class="font-bold text-4xl md:text-5xl text-white">Manage outbound email, SMS, and push notifications from one place.</h1>
            </div>
          </div>
        </div>
      </div>
    </header>

    <section class="bg-white">
      <div class="container mx-auto p-24">
        <div class="flex flex-col md:flex-row items-center justify-center -mx-6">
          <div class="w-full md:w-1/2 px-6 mb-0 md:mb-32">
            <figure>
              <img src="./assets/templates.png" alt="">
            </figure>
          </div>
          <div class="w-full md:w-1/2 px-6 mb-32">
            <h3 class="text-4xl mb-8">Create and edit <br class="hidden lg:inline-block"> templates online</h3>
              <p>Empower your team to craft and test messages without wasting valuable dev time.</p>
          </div>
        </div>
        <div class="flex flex-col-reverse md:flex-row items-center justify-center -mx-6">
          <div class="w-full md:w-1/2 px-6 mb-32">
            <h3 class="text-4xl mb-8">Deliver across <br class="hidden lg:inline-block"> multiple channels</h3>
              <p>Easily connect your favorite service providers to handle email, SMS, push and in-app delivery.</p>
          </div>
          <div class="w-full md:w-1/2 px-6 mb-0 md:mb-32">
            <figure>
              <img src="./assets/channels.png" alt="">
              </figure>
          </div>
        </div>
        <div class="flex flex-col md:flex-row items-center justify-center -mx-6">
          <div class="w-full md:w-1/2 px-6">
            <figure>
              <img src="./assets/integrate-sdk.png" alt="">
            </figure>
          </div>
          <div class="w-full md:w-1/2 px-6">
            <h3 class="text-4xl mb-8">Integrate within <br class="hidden lg:inline-block"> minutes</h3>
              <p>Use our clean, easy-to-use API and SDK’s written by developers, for developers.</p>
          </div>
        </div>
      </div>
    </section>

    <section>
      <div class="container mx-auto py-24">
        <div class="text-center mb-24">
          <h2 class="font-bold text-5xl mb-8">We’re currently in <br> private beta</h2>
            <p>Pigeon is free to use while in beta, but here’s what our <br> pricing will look like once we launch:</p>
        </div>
        <div class="flex flex-wrap -mx-6">
          <div class="w-1/2 md:w-1/4 flex flex-col px-6">
            <figure class="mb-2"><img src="./assets/pricing-free.png" alt=""></figure>
              <div class="ml-12 flex-1 mb-8">
                <h3 class="text-3xl text-pigeon-orange mb-6">Free</h3>
                <p class="mb-2">Unlimited templates</p>
                <p>Only for testing</p>
              </div>
              <div class="text-2xl ml-12 border-t border-grey-light pt-4">$<span class="font-bold text-4xl">0</span>/mo</div>
          </div>
          <div class="w-1/2 md:w-1/4 flex flex-col px-6">
            <figure class="mb-2"><img src="./assets/pricing-startup.png" alt=""></figure>
              <div class="ml-12 flex-1 mb-8">
                <h3 class="text-3xl text-pigeon-orange mb-6">Start up</h3>
                <p class="mb-2">Unlimited templates</p>
                <p class="mb-2">5 members</p>
                <p>1 project</p>
              </div>
              <div class="text-2xl ml-12 border-t border-grey-light pt-4">$<span class="font-bold text-4xl">9</span>/mo</div>
          </div>
          <div class="w-1/2 md:w-1/4 flex flex-col px-6">
            <figure class="mb-2"><img src="./assets/pricing-growth.png" alt=""></figure>
              <div class="ml-12 flex-1 mb-8">
                <h3 class="text-3xl text-pigeon-orange mb-6">Growth</h3>
                <p class="mb-2">Unlimited templates</p>
                <p class="mb-2">Unlimited members</p>
                <p>3 projects</p>
              </div>
              <div class="text-2xl ml-12 border-t border-grey-light pt-4">$<span class="font-bold text-4xl">19</span>/mo</div>
          </div>
          <div class="w-1/2 md:w-1/4 flex flex-col px-6">
            <figure class="mb-2"><img src="./assets/pricing-scale.png" alt=""></figure>
              <div class="ml-12 flex-1 mb-8">
                <h3 class="text-3xl text-pigeon-orange mb-6">Scale</h3>
                <p class="mb-2">Unlimited templates</p>
                <p class="mb-2">Unlimited members</p>
                <p>Unlimited projects</p>
              </div>
              <div class="text-2xl ml-12 border-t border-grey-light pt-4">$<span class="font-bold text-4xl">29</span>/mo</div>
          </div>
        </div>
      </div>
    </section>
    <section>
      <div class="container mx-auto p-24">
        <div class="flex flex-col md:flex-row items-center bg-pigeon-orange-light p-12 rounded-lg shadow-lg">
          <div class="w-full md:w-1/3 mr-8 mb-8 md:mb-0">
            <h2 class="font-bold text-white text-4xl mb-6">Sign up now for <br class="hidden md:inline-block"> early access</h2>
              <p class="font-medium text-white">Don’t miss out on our special <br class="hidden md:inline-block"> deal for early adopters!</p>
          </div>
          <div class="w-full md:w-2/3">
            <form action="">
              <input type="email" class="font-medium p-8 border border-white bg-pigeon-orange text-white rounded shadow focus:outline-none w-5/6" placeholder="Email address">
              <button type="button" class="font-bold text-sm bg-white px-6 py-4 rounded shadow -mx-8">SUBMIT</button>
            </form>
          </div>
        </div>
      </div>
    </section>

    <footer>
      <div class="container mx-auto p-24">
        <div class="flex justify-between text-sm">
          <div>
            <a href="#" class="text-grey-darker mr-4">Terms of service</a>
            <a href="#" class="text-grey-darker">Privacy policy</a>
          </div>
          <div class="text-grey-darker">&copy; 2018 Pigeon Inc.</div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  data() {
    return {
      bgImage: require('./assets/pigeon-bg.svg')
    }
  }
}
</script>


<style>
@tailwind preflight;
@tailwind components;
a {
  @apply no-underline;
}
.pigeon-bg {
  background-image: url('./assets/pigeon-bg.svg');
  width: 400px;
  @apply bg-no-repeat bg-contain;
}
@tailwind utilities;
</style>
