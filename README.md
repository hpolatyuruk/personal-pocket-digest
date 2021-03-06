# PocketDigest

<div align="center">
    <img alt="pocket digest" src="https://pocketdigest.xyz/static/images/pocket-email.jpg" />
</div>

PocketDigest is a personal service that brings all the links you saved in Pocket to your email with the preferences you choose.

<a href="https://pocketdigest.xyz/" target="_blank">Go to website ></a>

---

## How it works 

### Login in to your Pocket account

In order to start this service we need to first get you logged in to your Pocket account. 

### Connect with PocketDigest

Once you are logged in your Pocket account, you will need to connect it with PocketDigest app in order to proceed to the next step where you will set your email preferences. 

### Set your email preferences

Now you are connected. You will see a page where you will enter your email address and set all your email preferences such as email frequency, and link count per email. 

### All done

The links you save to Pocket will be delivered in your inbox according to the email preferences you set. Each time we send you an email, all the links will be archived in your Pocket account. So in this way we make sure that we do not send you the same link again and at the same time you are also sure that you can find that link in your Pocket archive whenever you want. 

## This is how an email looks like

<div align="center">
    <img alt="pocket digest" src="https://pocketdigest.xyz/static/images/pocket-digest-email.png" width="648" height="890" />
</div>

## Guide to Developers

As first step, clone the project to your local computer using the following command:

git clone https://github.com/hpolatyuruk/pocketdigest.git

One you copied it, in the project root folder create an .env file that includes the following environment variables and set the values you prefer:

* APP_PORT=
* POSTGRES_HOST=pocketdigest_db
* POSTGRES_PORT=5432
* POSTGRES_USER=postgres
* POSTGRES_PASSWORD=
* POSTGRES_DB=
* PGDATA=/pgdata
* POCKET_CONSUMER_KEY=
* SENDER_EMAIL
* SENDGRID_API_KEY=
* PGADMIN_DEFAULT_EMAIL=
* PGADMIN_DEFAULT_PASSWORD=
* PGADMIN_LISTEN_PORT=

Afterward, run the following docker-compose command to bring the PocketDigest app and the database up.

docker-compose -f docker-compose-dev.yml up

## Website

<a href="https://pocketdigest.xyz/" target="_blank">https://pocketdigest.xyz</a>

## Developer

### Huseyin Polat Yuruk

- [Website](https://huseyinpolatyuruk.com/)
- [Twitter (@hpolatyuruk)](https://twitter.com/hpolatyuruk)
- [Medium (@hpolatyuruk)](https://medium.com/@hpolatyuruk)