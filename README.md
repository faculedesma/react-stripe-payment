<p>
  <a href="https://stripe.com" rel="noopener" target="_blank"><img width="150" src="client/src/assets/stripe-logo.png" alt="stripe-logo"></a>
</p>

# React Stripe Payment

## How to run locally

This includes the React client for the sample and the server. Both runs independently.
Running a backend server is a requirement and a dependency for the React front-end to work.

To run the React client locally:

1. Install dependencies

From this directory run:

```sh
npm install
```

2. Start the react app

```sh
npm start
```

This will start the react server running on localhost:4242. Note that the
backend server runs on localhost:5252, but the React UI will be available at
localhost:4242. API requests to your backend are proxied by the
create-react-app server using the `proxy` setting in `./package.json`.
