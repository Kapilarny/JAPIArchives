# JAPI Archives

This is a repo used for storing artifacts necessary for JAPI updates

# Structure

In `manifests` folder we have the latest possible manifests for various things.
`JAPI` contains all updates both for `main` and `preload`.

All files have signed and unsigned versions.
The signed versions are available in the `signed` folders.
The signed versions differ only in the last 64 bytes, which contain the signature.