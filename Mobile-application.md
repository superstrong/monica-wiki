## Activate login through a mobile application

* You need to use the CLI to generate a new key specific to your application. You CAN'T generate this kind of key using Monica's UI.
* Run `php artisan passport:client --password` and copy the client ID and the client Number.
* Edit your .env file and add the following lines (replace the values with the two ones generated above)
```
MOBILE_CLIENT_ID=3
MOBILE_CLIENT_SECRET=qNkm0IFKE2mXxzi6zuedADU2Uris4qIgFHd4fJbVt
```

This should let users of the mobile application to access their account.