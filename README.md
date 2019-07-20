# Decentralized-Application-v0.1

## 1) sign out button handler to delete the user data and sign the user out.

document.getElementById('signout-button').addEventListener('click', event => {
    event.preventDefault()
    userSession.signUserOut()
    window.location = window.location.origin
  })
