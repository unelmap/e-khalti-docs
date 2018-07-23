# IPN for merchants

The e-Khalti can accept external requests for wallet deposit. The
interface can be used by merchants who have undergone complete
verification of the account and merchant. The user needs to perform
several steps to activate the merchant interface:

## Getting Started

### Prerequisites

Step 1

```
The user must perform full account verification.
```


Step 2
```
User must add the merchant project and the administrator must set
the enabled status.
```

The user must enter values:
```
Name - name merchant. This value is searchable on the store page
and displayed on the payment page.
```

```
URL site - site link merchant.
```

```
Status IPN link - an instant notification of payment will be sent to this
address. Available only when used HTML form.
```

```
Success link - the buyer will be redirected to this page after successful
payment. Available only when used HTML form.
```

```
Fail link - the buyer will be redirected to this page after fail payment.
Available only when used HTML form.
```

```
Merchant IPN password - this password is used to verify the payment
notification.
```

```
Logo - merchant's logo. Only GIF, JPEG, PNG. Max size - 5 MB.
```

```
Categories - available category merchant for section Shops and
Payments.
```

```
Show in Shops and payment? - if yes, the merchant will be displayed in the
section Shops snd Payments.
```

```
Who pays the fees? - user can choose who pays the commission of the
system.
```

```
Note for payment - note for payment via user account:
```

```
Comment for administration - any comment for the administrator
```

After activating the merchant administrator, developers can use HTML form
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.


## Contributing

Please read [CONTRIBUTING.md] for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

