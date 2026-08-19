# uYouEnhanced for AltStore & SideStore

Personal AltSource for uYouEnhanced 20.44.2 / uYou 3.0.4. The same source
remains available for AltStore. SideStore users on iOS 27 should use the direct
install route below because SideStore 0.6.3 can crash while saving a custom
source from the checkmark/Done screen.

## Install with SideStore

[Open the hosted SideStore installer](https://jessomadic.github.io/uYouEnhanced-AltStore/)

The installer uses SideStore's direct-install URL action and bypasses the
crashing Sources workflow. Open SideStore once, then tap **Install with
SideStore** on the hosted page.

The direct IPA is the same upstream-published file referenced by this source.
It was validated as an ARM64 IPA with bundle identifier
`com.google.ios.youtube`, minimum iOS 16.0, and SHA-256
`97a867a179964aeb7e21e1bd069cbfc7681914894a9a89b5654c369be4aed356`.

## Add to AltStore

Source URL:

```text
https://raw.githubusercontent.com/Jessomadic/uYouEnhanced-AltStore/main/apps.json
```

On the iPhone, open AltStore, choose **Sources**, tap **+**, paste the URL,
and add the source. Install **uYouEnhanced** from the new source.

## Why this source exists

The upstream source currently routes its IPA through a TinyURL preview page.
AltStore and SideStore expect a direct IPA response, so the preview page can
make the download appear to be missing. This source points directly to the
same IPA URL published in the upstream source.

The canonical AltSource is retained for AltStore and for future SideStore
versions where the custom-source save crash is resolved. SideStore's hosted
direct-install route uses the exact same IPA URL, version, size, and SHA-256.

The IPA is not stored in this repository. uYouEnhanced is maintained by
[arichornlover and its contributors](https://github.com/arichornlover/uYouEnhanced).
