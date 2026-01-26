# Public Wake Arena reports
This repository collects all our Wake Arena reports that have been published by our clients.

These reports were created by [Wake Arena](https://ackee.xyz/wake/arena), an automated vulnerability analysis tool.

For audit reports created during manual review by Ackee auditors see the [Ackee-Blockchain/public-audit-reports](https://github.com/Ackee-Blockchain/public-audit-reports) repository.


## Verifying report signatures
Reports have a signature that can be used to verify that the PDF has not been modified when downloaded from a source other than this repository.

- Download the [public.key](https://github.com/Ackee-Blockchain/wake-arena-reports/blob/main/public.key) file
- Import it with `gpg` and verify

```
gpg --import public.key
gpg --verify <report>.pdf.sig <report>.pdf
```
