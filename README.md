<h1>Laravel Project for AirBnb Clone</h1>
<hr>
<h2>Technologies used: </h2>
<ul>
	<li>Html 5</li>
	<li>Css</li>
	<li>Bootstrap</li>
	<li>JavaScript and Jquery</li>
	<li>Laravel 7</li>
	<li>MySql</li>
	<li>and... BrainTree for payment, Chart.js, TomTom Maps SDK, Handlebars</li>
</ul>

<h2>Installation</h2>
<p>
    composer install
</p>
<hr>
<p>
    npm install
</p>
<hr>
<p>
   cp .env.example .env
</p>

<hr>
<p>
   php artisan key:generate
</p>
<hr>

<hr>
<p>
  php artisan migrate
</p>
<hr>
<p>
  php artisan db:seed
    (must change fzaninotto/faker images cause link to img are deprecated)
</p>
<hr>
<h3>Inside .env file add: </h3>
<h6>Db Connection</h6>
<p> DB_CONNECTION=mysql</p>
<p>DB_HOST=127.0.0.1</p>
<p>DB_PORT=yourPort</p>
<p>DB_DATABASE=yourDb</p>
<p>DB_USERNAME=yourUserName</p>
<p>DB_PASSWORD=yourPwd</p>
<h6>Brain Tree credential (only for payment)</h6>
<p>BT_ENVIRONMENT=sandbox</p>
<p>BT_MERCHANT_ID=yourID</p>
<p>BT_PUBLIC_KEY=yourPublicKey</p>
<p>BT_PRIVATE_KEY=yourPrivateKey</p>
