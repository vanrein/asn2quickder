# THIS PACKAGE HAS BEEN DISSOLVED

This was a branch of [asn1ate](https://github.com/kimgr/asn1ate)
but we have decided to restructure:

  * The changes made to `asn1ate` have been put into a
    [pull request](https://github.com/kimgr/asn1ate/pull/47) and donated back
  * Our own translater `asn2quickder` has been integrated into its targeted tool
    [Quick DER](https://github.com/vanrein/quick-der)

If you were packaging `libquickder` and its build dependency on `asn2quickder`,
please shift your focus; the build dependency is now `asn1ate` and you will get
an extra file `bin/asn2quickder` installed into your prefix.

Note that you can silently drop `asn2quickder` in your distribution, at your
own pace; the `master` branch has remained unchanged but will no longer be
maintained.  The only thing that will change is the *default* branch shown
at GitHub, which will be this dissolving branch.

Thank you for understanding,

-Rick
