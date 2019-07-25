# Decentralized-Application-v0.1

## 1) sign out button handler to delete the user data and sign the user out.

document.getElementById('signout-button').addEventListener('click', event => {
    event.preventDefault()
    userSession.signUserOut()
    window.location = window.location.origin
  })
## 2) authentication processed at client side.

JSON web tokens passed through URL query strings, application communicates with authRequest and  user processes authResponse. Vice versa through redirectToSignIn() when user chooses to sign in.

an instance specific, ephemeral transit key is used to generate token (authRequest here) and public part of the key is used to encrypt a private key for authResponse.
## (ip) adding gaia and omniauth with rails.
