# Security Reporting

Have you found a security vulnerability or bug affecting the 2FA Directory or Passkeys Directory?  
Get in touch with us!

## Vulnerability Scope

[2factorauth][about] hosts the 2FA Directory [website][2fa_website]
and [API service][2fa_api] along with the Passkeys Directory [website][pk_website] and [API service][pk_api].  
We also manage the GitHub repositories on [github.com/2factorauth][github].  
Vulnerabilities directly related to the code in these repositories can be reported to us.  
If you've found an issue with one of our dependencies, please report your findings directly to the dependency in
question.

> [!Note]
> Before reporting, please keep in mind that the Directories are static websites with API services that are public to everyone.  
> Therefore, potential DOM and cookie exfiltrations are outside our security vulnerability scope.

## Reporting Vulnerabilities

Please report your findings through our [Security advisory platform][advisory].  
If you're unable to use GitHub, send us an email instead at <a href="mailto:contact@2fa.directory">contact@2fa.directory</a>.
PGP is available using the key [0xDD315F4D][pgp].

> [!Important]  
> Reports from automated security scans will be discarded.

[2fa_api]: https://2fa.directory/api/
[2fa_website]: https://2fa.directory/
[about]: https://2fa.directory/about/
[advisory]: https://github.com/2factorauth/twofactorauth/security/advisories/new
[github]: https://github.com/2factorauth
[pk_api]: https://passkeys.2fa.directory/api/
[pk_website]: https://passkeys.2fa.directory/
[pgp]: https://keys.openpgp.org/vks/v1/by-fingerprint/66906F90EA58EC3FA5DC5B3A61339316DD315F4D
