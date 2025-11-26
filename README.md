<p>To run this project:</p>

<p>1. need to create a .env file in the server folder and add</p>
<br>DB_USER
<br>DB_PASS
<br>ACCESS_TOKEN_SECRET
<br>NODEMAILER_USER=
<br>NODEMAILER_PASS=
<br>PAYMENT_SECRET_KEY<br>
<br>
<br>2. need to create a .env.local file in client folder and add
 <br>VITE_apiKey
  <br>VITE_authDomain
  <br>VITE_projectId
 <br> VITE_storageBucket
  <br>VITE_messagingSenderId=
  <br>VITE_appId
  <br>VITE_measurementId
  <br>VITE_IMGBB_API_KEY
  <br>VITE_API_URL
  <br>VITE_STRIPE_PUBLISHABLE_KEY
<br>
<br>After that go to the command line and enter server folder and client folder and write 
<br>npm i
<br>after install all dependency
<br>write
<br>npm run dev
<br>both client and server command line