# Week 1 Weekend Assignment

## How it works now:

I have it set up to accept public key addresses and a private key on the front end.  These are pulled out on the server and validated.  If the private key is wrong, the server will log an error message.  If the validation passes, the transaction will process and the server will log an error message.

Right now in order to know if the validation passed, you need to have the server logging open

## TODOs:

- [ ] handle the case where there  aren't any inputs (form validation)
- [ ] output an error to the UI if the key verification fails so the user knows something happened
- [ ] re-arrange the UI so that the private key field is on the bottom (it would be better UI to enter the sender/receiver, then the private key)
- [ ] instead of entering the message in the .js file, have an input box for a message
