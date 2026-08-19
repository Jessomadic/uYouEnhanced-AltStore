# uYouEnhanced AltStore & SideStore Source

Personal AltSource for uYouEnhanced 20.44.2 / uYou 3.0.4. The same source
works in both AltStore and SideStore.

## Add to SideStore

[Add uYouEnhanced to SideStore](sidestore://source?url=https%3A%2F%2Fraw.githubusercontent.com%2FJessomadic%2FuYouEnhanced-AltStore%2Fmain%2Fapps.json)

If the link is not clickable, copy this source URL:

```text
https://raw.githubusercontent.com/Jessomadic/uYouEnhanced-AltStore/main/apps.json
```

On the iPhone, open SideStore, choose **Sources**, tap **+**, paste the URL,
and add the source. Install **uYouEnhanced** from the new source.

The `sidestore://` link requires SideStore to already be installed.

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

SideStore officially supports AltStore sources, so a separate duplicate JSON
file is not required. Keeping one canonical source also ensures both stores
receive the same version, size, SHA-256, and compatibility metadata.

The IPA is not stored in this repository. uYouEnhanced is maintained by
[arichornlover and its contributors](https://github.com/arichornlover/uYouEnhanced).
