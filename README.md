# Hello, Svelte World!

You can use this sample project to learn how to secure a simple Svelte application using Auth0.

![Hello, Svelte World!](https://cdn.auth0.com/blog/hello-auth0/hello-svelte.png)

The `starter` branch offers a functional application that consumes local data to hydrate the user interface. All the starter application routes are public.

The goal is to use Auth0 to get an ID token to hydrate the user profile information present in the `/profile` page and to get an access token to make a secure call to an external API to hydrate the messages present in the `/external-api` page.

## Get Started

Install the project dependencies:

```bash
npm install
```

Create a `.env` file under the root project directory and populate it as follows:

```bash
API_SERVER_URL=http://localhost:6060
```

Run the application:

```bash
npm run dev
```

Visit [`http://localhost:4040/`](http://localhost:4040/) to access the starter application.