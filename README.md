# Ionic Tutorial

Let's do the Ionic Tutorial using Cloud9 IDE.

## Get started

- Start a [Cloud9 IDE](https:/c9.io) workspace
- Install NodeJS 6, Ionic and dependencies
```
nvm install 6
nvm use 6
npm install -g ionic cordova
```

Initialize and run your app in the browser:
```
ionic start app tutorial
cd app
ionic serve --port $PORT
```

After create your account at http://ionic.io,
login and link this app to Ionic View.
```
ionic login
ionic link
```

Make the first dependencies to [Ionic View](http://view.ionic.io/)
```
ionic upload --note "First deployment" --deploy production
```

## References

- [Ionic Tutorial](https://ionicframework.com/docs/intro/tutorial/)
- [Install Node.js for Debian based Linux](https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions)
