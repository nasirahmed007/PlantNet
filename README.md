To run this project:

1. need to create a .env file in the server folder and add
DB_USER
DB_PASS
ACCESS_TOKEN_SECRET
NODEMAILER_USER=
NODEMAILER_PASS=
PAYMENT_SECRET_KEY

2. need to create a .env.local file in client folder and add
 VITE_apiKey
  VITE_authDomain
  VITE_projectId
  VITE_storageBucket
  VITE_messagingSenderId=
  VITE_appId
  VITE_measurementId
  VITE_IMGBB_API_KEY
  VITE_API_URL
  VITE_STRIPE_PUBLISHABLE_KEY

After that go to the command line and enter server folder and client folder and write 
npm i
after install all dependency
write
npm run dev
in both command line