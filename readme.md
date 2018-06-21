# GAPI Playground

Playing around with the Google API for spreadsheets - and may be other Google APIs...

## Keys

As we don't want to have our private keys for Google or other systems in the GitHub Repo, we _hide_ them in a private file. To add your key, create a file `keys.js` that should look as follows:

```javascript
// Make sure this file is added to .gitignore

keys = {
  google: {
    clientID: 'YOUR KEY',
    clientSecretKey: 'YOUR KEY',
    apiKey: 'YOUR KEY'
  }
};
```
