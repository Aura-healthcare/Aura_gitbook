# Security
## Storing data
Assume the hacker has root access to your device. No emplacement is secure.

| Android | iOS   |
|---------|-------|
| Use Keystore and Store your files after encryption. The best practice is to store your app in `/app/data/packageofyourapp`    | Use Keychain  |

Hacker can decompile your app. Do not expose useful information direction in your code or in any ressource files.

| Android | iOS   |
|---------|-------|
| Enable Proguard (obfuscation) / Store sensible secret_key in BuildConfig    | Use info.plist  |


## Communication
Use Https to secure your communication with your server.

Use a certificate pining if possible.

## Webview
If you use webview enable `javascript` only if necessary.


## References
https://github.com/OWASP/owasp-mstg
https://developer.android.com/topic/security/
