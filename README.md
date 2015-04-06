toastwallet is a real standalone bitcoin client based on breadwallet (see fork).

This will be maintained as a fork, merging in the latest breadwallet - incorporating
additional features or changes as I selfishly decide to implement.  See issue https://github.com/thesoftwarejedi/breadwallet/issues/1 for
the reason this fork was created.  My daughter is 11 years old and has trouble with
the BTC conversion from bitpay payment screens to bits.  At the same time, I support
breadwallet, its pure SPV model, and strong security practices.  The author of breadwallet,
@voisine suggested that I fork and implement the changes that we disagree on.  He loves
my daughter less than I do, understandably :)  So,here we are.

**WARNING:** installation on jailbroken devices is strongly discouraged

Any jailbreak app can grant itself access to every other app's keychain data
and rob you by self-signing as described [here](http://www.saurik.com/id/8)
and including `<key>application-identifier</key><string>*</string>` in its
.entitlements file.
