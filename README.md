# Testing and Previewing Public Embedding
This repository contains some simple html pages embedding public projects from the lfview-*.test.seequent.xyz
development servers. These examples are being hosted at https://seequent-firebase-testing.firebaseapp.com. The goal
is to be able to easily preview and test public embedding with our development servers.
# Updating the examples
1. Check if you have firebase-tools installed, `firebase --version`.
   * If not, install firebase-tools with npm `npm install -g firebase-tools`
1. Login to firebase with `firebase login`
1. Run `firebase serve` to host the files locally and test it works as you expect.
1. Deploy to the server with `firebase deploy --only hosting`
