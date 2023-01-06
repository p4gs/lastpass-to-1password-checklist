# Moving from LastPass to 1Password
>⚠️ LastPass recently [experienced a security breach](https://www.wired.com/story/lastpass-breach-vaults-password-managers/) that resulted in all customers’ vault data being stolen (most sensitive data encrypted but some less sensitive data unencrypted). This guide is intended to help LastPass users to migrate to a much better password manager, 1Password, while also protecting their online accounts that are now at an increased risk of being compromised.

## Install 1Password apps and extensions

- [ ] Install 1Password 8 app on [Mac](https://downloads.1password.com/mac/1Password.zip) or [Windows](https://downloads.1password.com/win/1PasswordSetup-latest.exe) computer
- [ ] Install 1Password [Chrome extension](https://chrome.google.com/webstore/detail/1password-%E2%80%93-password-mana/aeblfdkhhhdcdjpifhhbdiojplfjncoa) on computer
- [ ] Install 1Password 8 [iPhone / iPad app](https://apps.apple.com/app/id1511601750?mt=8) on all iPhones and iPads  
- [ ] Make sure you have the [latest software update](https://support.apple.com/en-us/HT204204) installed!

## 1Password account setup

>ℹ️ Use [this link](https://start.1password.com/sign-up/family?c=TROY-MXIEYXAH) for 50% off your first year of a new 1Password Families account for you and 5 other people (thanks, [Troy Hunt](https://www.troyhunt.com/a-password-manager-isnt-just-for-christmas-its-for-life-so-heres-50-percent-off/)!)

- [ ]  Create [1Password account](https://start.1password.com/sign-up/plan) (more info about each plan option [here](https://1password.com/sign-up/))
- [ ]  Use a totally different master password from the one you used with LastPass 
- [ ]  Setup [two-factor authentication](https://my.1password.com/profile/2fa) on 1Password account
- [ ]  Use “Security Key” option if you're able to
- [ ]  Print 1Password Emergency Kit, write down password on it, and store in fireproof safe (or somewhere else that’s physically secure)
- [ ]  Delete Emergency Kit PDF and empty Recycle Bin / Trash to permanently delete it

## Import LastPass data to 1Password account

- [ ]  [Export LastPass data](https://support.1password.com/import-lastpass/) to CSV file
- [ ]  [Import LastPass file](https://my.1password.com/import/lastpass) into 1Password
- [ ]  Move LastPass file to Recycle Bin / Trash and empty it to permanently delete it

## Secure your online accounts

>ℹ️ Try using [1Password Watchtower](https://support.1password.com/watchtower/) to hone in on which of your accounts are most at risk. 
>
>Advanced users may want to check out this [account hardening guide](https://justinpagano.substack.com/p/protecting-against-a-password-manager-8f6) for additional steps to take to secure your online accounts.

- [ ]  Use 1Password to change all passwords that were stored in LastPass
- [ ]  It can help to use the list of items displayed in your LastPass account as a sort of “checklist” where you delete each account after you’ve finished changing its password until nothing is left
- [ ]  Enable two-factor authentication on all accounts that do not have it (this will protect your accounts going forward regardless of how a password of yours gets stolen)
- [ ]  [Permanently delete all items](https://support.lastpass.com/help/permanently-delete-items-lp020012) from LastPass account
- [ ]  [Delete / close LastPass account](https://lastpass.com/my.php)
- [ ]  Change 1Password master password (in the event the people who breached LastPass end up guessing your LastPass master password)

## FAQs

### "Why should I move off LastPass now?"
-  Jeremi Gosney wrote a [brilliant post](https://archive.is/Mumto) on infosec.exchange laying out a variety of reasons to move off LastPass  

### "Why move to 1Password?"
-   My recommendation to move to 1Password is based on a few reasons
	- 1Password's [security model](https://1passwordstatic.com/files/security/1password-white-paper.pdf) is stronger than LastPass', especially in light of this incident that puts customers' data at risk of offline brute force attacks. 1Password has long incorporated a [Secret Key](https://support.1password.com/secret-key-security/) to protect customer data from offline brute force attacks. Even if your 1Password master password is a single character long, the Secret Key acts as an "extension" of your password with 26 randomly generated alphanumeric characters
	- 1Password is solely focused on building password/secrets management software. That puts them in a better position to be laser focused on keeping their security model up-to-date given an ever-changing threat landscape
	- They've been consistently focused on creating a really polished UI and UX for years now, something that LastPass always struggled with and was potentially a sign of poorer quality control in their software in general.
	- From both a security model perspective and a UI/UX perspective, I personally think 1Password has an edge over BitWarden (sorry, BitWarden die hard fans). I think BitWarden has solid tech, and [I recommend using them](https://justinpagano.substack.com/i/90282736/password-manager-apps) in tandem with 1Password for folks who are looking to max out the security of their password manager setup. But it doesn’t make the cut for me as a primary password manager, especially for non-technical folks where UI/UX matters a lot more (my parents will attest to this endlessly)
