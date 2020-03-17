# How I handle my credentials

> TL;DR: I use a password manager and enable 2FA on my most important accounts. The 2FA app I use has automatic backups and is protected with a PIN number on my phone for extra security.

I’m going to keep it simple and concise:

_**If you use the same password for different accounts, one getting hacked means the other is going to be hacked as well. DO NOT reuse passwords, unless you truly don’t have a problem with getting your accounts hacked.**_

## Password manager

A password manager is a solution to an everyday problem. It generates a random and complex password, saves it for you, and autofills it when you need it. This is excellent for three reasons:

-	You don’t have to come up with a new unique password and remember it.
-	You will never use the same password twice.

The password manager I use and recommend is [Bitwarden](https://bitwarden.com/). Here’s a video on how to use it https://www.youtube.com/watch?v=oh7FtqCK5Z0.

## Second factor authentication

A second factor authentication protects you from someone else using your passwords. It’s a way of proving it’s really you who wishes to enter into whatever website you’re trying to login, and not a hacker, even if they got your password.

I use the Microsoft Authenticator app with [cloud backup](https://docs.microsoft.com/es-es/azure/active-directory/user-help/user-help-auth-app-backup-recovery) enabled. The app generates a new 6 digits code every 30 seconds. After your password manager autofills your username and password, the website will ask for this code, which you need to enter to finish the login process to verify your identity.

It takes me at most 30 extra seconds to login into Amazon and PayPal and in exchange, I have a much higher sense of security.
Check out https://twofactorauth.org/ for a list of websites that support 2FA and how to enable it.

### Final thoughts

I actually don’t have every password on Bitwarden, these are the ones I keep in my head:

-	My personal email password
-	My work PC login password
-	My home laptop login password
-	My PGP password (if you don’t know what PGP is, ignore this)
-	My password manager’s master password

For an extra layer of security, I protect my important apps on my phone with an extra PIN number that I also keep in my memory. Therefore, even if my phone gets stolen while unlocked, they still can’t access my sensitive apps.

Until next time,

m.
