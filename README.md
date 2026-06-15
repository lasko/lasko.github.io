# lasko.github.io

Previously hosted an Android App Links `assetlinks.json` for the Gobo OGS client's OAuth redirect.
That approach was replaced by a loopback redirect (`http://127.0.0.1:52847/`, RFC 8252 §7.3), which
keeps the auth code on-device and needs no hosted file — so the assetlinks file was removed.
