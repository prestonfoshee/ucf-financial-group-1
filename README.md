# UCF Financial App Training Guide - Group 1

This app was done as a school assignment and is for educational purposes only. It is heavily inspired by the existing UCF Financial mobile app, and is a rework based on the original team's project from Fall 2021. It is built with a full-stack JavaScript framework based on Vue.js called Nuxt.js [(documentation)](https://nuxtjs.org/docs/get-started/installation), and Supabase for the database [(documentation)](https://supabase.com/docs).

The UCF Financial App is primarily intended to be an informational resource for UCF students, providing information such as available financial aid options, scholarships, coupons and discounts, and financial literacy/events. Although it is mostly informational, the app also allows students to log in and keep track of their personal financial information which will be visible on their profile page. They can also keep track of their budget and the amount of money they have left for each semester for different categories using the budget calculator, which will also be visible on the student's profile page.

## Installation and set up

### Requirements

 - git
 - stable version of Node.js (16.14.2) & npm (8.3.0)

### In your terminal, run the following commands:

```bash 
# clone the repository
$ git clone https://github.com/prestonfoshee/ucf-financial-group-1.git

# change directories to the to access the files
$ cd ucf-financial-group-1

# install the dependencies
$ npm install

# start the development server on localhost:3000
$ npm run dev
```

## Important directories

### `pages/`

This directory contains your application views and routes. Nuxt will read all the `*.vue` files inside this directory and setup Vue Router automatically.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/get-started/routing).

### `components/`

The components directory contains your Vue.js components. Components make up the different parts of your page and can be reused and imported into your pages, layouts and even other components.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/components).

### `layouts/`

Layouts are a great help when you want to change the look and feel of your Nuxt app, whether you want to include a sidebar or have distinct layouts for mobile and desktop.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/layouts).

### `store/`

This directory contains your Vuex store files. Creating a file in this directory automatically activates Vuex.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/store).

### `assets/`

The assets directory contains your uncompiled assets such as Stylus or Sass files, images, or fonts.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/assets).

## Creating and editing pages and components

### Creating pages

A page can be created by making a new file inside the `pages/` folder ending in `.vue`. These file names should be all lowercase, and will be the same as the name of the route in the URL.

### Editing pages

A page can be edited by adding all of the HTML inside a `template` tag that has another root element such as a `div` tag inside it. All the necessary JavaScript should be written inside a `script` tag.

A basic example of a Nuxt page looks something like this:

```
<template>
	<div>
		<h1>My favorite color is {{ color }}</h1>
	</div>
</template>

<script>
	export default {
		data() {
			return {
				color: 'blue',
			}
		},
	}
</script>
```

### Components

Unlike pages, components should have the first letter of each word in its name capitalized, like `LoginButton.vue`, for example.

On the page that you want to use the component on, you need to import it and register it as a component like so:

```
<script>
	import LoginButton from '../components/LoginButton.vue'
	export default {
		components: {
			LoginButton,
		},
	}
</script>
```

## Adding media

## Building for production and launching server

### Changing the base path via the `base` value of the `router` property in the `nuxt.js.config` file located in the project's root directory

Below is an example of our project's base path for deploying to the UCF web server:

``` 
export default {
	router: {
		base: '/~pr918790/ucf-financial-group-1/dist/'
	}
}
```

The `base` value should be set to the string that you want your page routes to come after in the url. Since the base in the code snippet above is for the UCF web server, the URL for the Budget Calculator page, for example, would be https://students.cah.ucf/~pr918790/ucf-financial-group-1/dist/budget-calculator. More information about the `router` property can be found [in the documentation](https://nuxtjs.org/docs/configuration-glossary/configuration-router/#base).

### Building - In your terminal, run the following commands:

```bash
# standard build process

# build app for production
$ npm run build
# 
$ npm run start

# generating static project (if you want to deploy to UCF server)
$ npm run generate
```

If you are generating a static site and run the `npm run generate` command, a folder called `dist/` will be created in the root of the project directory. This folder will contain all the production-ready HTML files and assets that are necessary to deploy and run the static site. More information about the `dist/` folder can be found [In the documentation](https://nuxtjs.org/docs/directory-structure/dist#dist-directory).
