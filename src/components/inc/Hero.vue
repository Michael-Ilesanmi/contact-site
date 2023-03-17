<template>
  <main 
    class="bg-no-repeat bg-center bg-cover bg-[url('https://cdn.pixabay.com/photo/2023/03/06/15/45/coffee-7833769_960_720.jpg')] min-h-screen pt-24 ">
    <div class="container flex space-x-24 items-center justify-between">
        <div class="w-3/6 flex flex-col justify-center h-full space-y-6 text-white">
            <h2 class="font-medium text-2xl text-white">
                Top Rated Software Development Contractors
            </h2>
            <h1 class="font-bold text-white text-5xl">
                Hire Software Development Contractors, Effortlessly.
            </h1>
            <p class="text-2xl">
                We provide you with experienced software development contractors, exactly when you need them. Highly responsive and in your timezone.
            </p>
        </div>
        <form @submit.prevent="false" class="bg-[rgb(229,231,235,0.7)] py-6 px-12 w-2/6">
            <h2 class="text-blue-600 text-xl font-bold text-center">
                Let's connect to help you and your team.
            </h2>
            <fieldset class="flex flex-col space-y-4 font-medium my-4">
                <input type="text" placeholder="Your Name" class="focus:outline  focus:outline-4
                 focus:rounded-none p-3 focus:outline-blue-400 font-medium invalid:outline invalid:outline-red-600 invalid:outline-1" required />
                <input type="email" placeholder="Your Work Email" class="focus:outline  focus:outline-4
                 focus:rounded-none p-3 focus:outline-blue-400 font-medium invalid:outline invalid:outline-red-600 invalid:outline-1" required />
                <textarea 
                    name="message" 
                    id="contact-message" 
                    cols="30" 
                    rows="10"
                    class="focus:outline  focus:outline-4 focus:rounded-none p-3 focus:outline-blue-400 font-medium invalid:outline invalid:outline-red-600 invalid:outline-1" 
                    required
                    placeholder="What can we do for you?"></textarea>
            </fieldset>
            <button 
                type="submit"
                class="bg-yellow-500 rounded-md w-fit mx-auto text-center font-semibold px-4 py-3 text-black"
                >
                Jump-Start Your Projects
            </button>
        </form>
    </div>
    <div class="bg-gray-900 py-8 mt-16">
        <div class="container">
            <div class="grid grid-flow-col items-center">
                <p class="font-semibold text-lg text-gray-400">
                    Trusted by startups and Fortune 500 companies
                </p>
                <div class="grid grid-flow-col gap-8 w-fit">
                    <img src="https://cdn.cdnlogo.com/logos/t/3/tens.svg" class="max-h-8 grayscale" alt="" />
                    <img src="https://cdn.cdnlogo.com/logos/p/61/pinterest-2.svg" class="max-h-8 grayscale" alt="" />
                    <img src="https://cdn.cdnlogo.com/logos/i/25/interjet-transparent.svg" class="max-h-8 grayscale" alt="" />
                    <img src="https://cdn.cdnlogo.com/logos/s/23/shell-helix-ultra-simple.svg" class="max-h-8 grayscale" alt="" />
                    <img src="https://cdn.cdnlogo.com/logos/y/12/youtube.svg" class="max-h-8 grayscale" alt="" />
                    <img src="https://cdn.cdnlogo.com/logos/f/23/facebook.svg" class="max-h-8 grayscale" alt="" />
                    <img src="https://cdn.cdnlogo.com/logos/s/35/sia-new-circle-transparent.svg" class="max-h-8 grayscale" alt="" />
                </div>
                
            </div>
        </div>
    </div>
  </main>
</template>

<script>
export default {

}
</script>

<style>

</style>