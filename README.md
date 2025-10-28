# My FairPhone 6 Notes

These are my notes for the FairPhone 6 running **Google-enabled Android**. These notes may or may not be helpful if you're using the [/e/OS](https://e.foundation/e-os/) version.

## Apps

### [MitID](https://play.google.com/store/apps/details?id=dk.mitid.app.android) 🇩🇰

#### Missing link association

**Symptom**: Instead of the MitID app, a page opens in your browser.

**Solution**:

* Go to *Apps*
* Go to *Default Apps*
* Go to *Opening links*
* Go to *MitID*
* Ensure *Open supported links* is enabled
* Ensure any additional links are enabled too

### [MobilePay](https://play.google.com/store/apps/details?id=dk.danskebank.mobilepay) 🇩🇰 🇳🇴 🇸🇪

#### Browser misbehaving

**Symptom**: "*The authentication failed. Please try again later*" during validation flow.

**Solution**:

* Remove app from old phone (you can always reinstall on the old phone if everything else fails)
* Force stop + clear data for Chrome
* Select Chrome as default browser
* Start Chrome and complete first-time wizard
  * DO NOT SELECT PRIVACY PROTECTION
* Force stop + clear data for MobilePay (if you've attempted this before)
* Run MobilePay and complete validation procedure
* Change default browser back to Firefox etc.

#### Locked out

**Symptom**: *Error E4005* (Account locked by MobilePay security - happens relatively quickly if you keep retrying)

**Solution**: Call/[chat](https://mobilepay.dk/) them to get it removed.
