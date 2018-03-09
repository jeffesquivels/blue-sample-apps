# Sample ed25519 Signature and Key Derivation App for Ledger Blue & Ledger Nano S

This application is a port of the [samplesign](../blue-app-samplesign)
demo to the [ed25519](https://ed25519.cr.yp.to/) signing algorithm. It
also demonstrates SLIP-0010 key derivation.

Run `make load` to build and load the application onto the device. After
installing and running the application, you can run `demo.py` to test a
signature over USB.

Note that in order to run `demo.py`, you must install the `ed25519` Python
package:

```
pip install ed25519
```

See [Ledger's documentation](http://ledger.readthedocs.io) to get started.
