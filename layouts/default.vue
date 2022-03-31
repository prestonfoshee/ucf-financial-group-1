<template>
<main class="min-h-screen bg-black">
        <section class="flex justify-between items-center px-16 py-6">
            <div class="flex items-center">
                <svg width="57" height="57" viewBox="0 0 57 57" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M28.5 57C44.2401 57 57 44.2401 57 28.5C57 12.7599 44.2401 0 28.5 0C12.7599 0 0 12.7599 0 28.5C0 44.2401 12.7599 57 28.5 57ZM29.8117 17.2729C34.1995 14.5786 41.3072 13.8376 44.8833 13.634C46.0853 13.5659 47.0876 14.4843 47.087 15.6436V37.7585C47.087 38.8209 46.2301 39.7072 45.128 39.7655C41.8997 39.9357 35.3708 40.5576 30.8564 42.8369C30.1614 43.1877 29.3373 42.7099 29.3373 41.9538V18.135C29.3373 17.7894 29.5089 17.4588 29.8117 17.2729ZM11.7044 13.634C15.2804 13.8382 22.3881 14.5786 26.7753 17.2729C27.0787 17.4595 27.2497 17.7769 27.2497 18.1232V41.9584C27.2497 42.7125 26.4281 43.1897 25.7351 42.8395C21.2207 40.5589 14.6885 39.9363 11.459 39.7662C10.3568 39.7085 9.5 38.8222 9.5 37.7592V15.6436C9.5 14.4843 10.5023 13.5659 11.7044 13.634Z" fill="#FFC904"/>
                </svg>
                <div class="flex items-center space-x-8">
                    <div class="px-6">
                        <h1 class="text-2xl text-main-gold font-medium uppercase">University of Central Florida</h1>
                    </div>
                    <!-- <Nav /> -->
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
