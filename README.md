# laravel_vuejs

replace the LaravelProject with your project name

laravel new LaravelProject
Install Vue.js on your Laravel 8 application
run the following commands

composer require laravel/ui
php artisan ui vue
php artisan ui vue --auth
npm install 
npm run dev
npm run watch
Now that you have installed everything you need, go to a blade view and add the following code inside <body></body>

<div id="app">
  <example-component />
</div>
<script src="{{ mix('/js/app.js') }}"></script>
If you did everything right you will see the following text on the rendering of your view

Example Component
Im an example component.
And in your console: Component mounted.

