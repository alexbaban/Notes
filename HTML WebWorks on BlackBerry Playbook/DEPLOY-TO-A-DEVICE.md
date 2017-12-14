# Deploy to a device

## Before you begin

* make sure that your BlackBerry PlayBook tablet is on the same network as your computer
* make sure that your BlackBerry PlayBook tablet is in ***Development Mode***

## Create a debug token

At a command prompt, navigate to `blackberry-tablet-sdk\bin` in your BlackBerry PlayBook OS SDK folder.

Type the following command:

`blackberry-debugtokenrequest -storepass <KeystorePassword> -devicepin <device PIN> <debug_token_file_name.bar>`

Example:

`blackberry-debugtokenrequest -storepass <KeystorePassword> -devicepin <device PIN> "C:\BlackBerryApps\DebugToken.bar"`

## Install a debug token

At a command prompt, navigate to `blackberry-tablet-sdk\bin` in your BlackBerry PlayBook OS SDK folder.

Type the following command:

`blackberry-deploy -installDebugToken <path to debug token> -device <Development Address> -password <device password>`

Example:

`blackberry-deploy -installDebugToken "C:\BlackBerryApps\DebugToken.bar" -device 192.168.0.108 -password <device password>`