# slotbox-cms-assets

Staging area for images on their way into the Vantage Retail CMS media library.

The CMS `upload-media` tool fetches by public https URL only — it cannot accept
bytes or a local file. Artwork is optimised locally, pushed here, pulled into the
media library once, and served from the CMS thereafter. Nothing here is a live
dependency of any site; these files exist only to be fetched once.

Public-facing Slotbox marketing assets only. No credentials, no customer data.
