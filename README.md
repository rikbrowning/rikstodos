# Riks Todos

## Get started

Run the following commands

```js
npm install
bower install
```

Update `firebase-app` in `src/my-app.html` to use your values for `api-key`, `auth-domain` and `database-url` attributes.

## Deploy to firebase

To deploy to firebase run the following commands. Remember to set your public folder to `build/bundled`.

```js
npm install -g firebase-tools
firebase login
firebase init
polymer build
firebase deploy
```
