<template>
<main class="min-h-screen bg-black">
        <section class="flex justify-between items-center px-16 py-3">
            <div class="flex items-center">
                <svg width="55" height="55" viewBox="0 0 55 55" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <circle cx="27.5" cy="27.5" r="27.5" fill="#FFC904"/>
                </svg>
                <div class="flex items-center space-x-8">
                    <div class="px-6">
                        <h1 class="text-2xl text-main-gold font-medium uppercase">University of Central Florida</h1>
                    </div>
                </div>
            </div>

            <div class="flex space-x-10 text-main-gold">
                <a href="/logout" :text="'Sign up'" as="button" method="post">
                    Logout
                </a>
            </div>
        </section>

        <section class="sm:py-10 sm:px-24 px-8 py-8">
            <div class="max-w-screen-3xl mx-auto">
              <Nuxt />
            </div>
        </section>
    </main>
</template>
