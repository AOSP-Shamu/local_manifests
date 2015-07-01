# AOSP-Shamu

This is the local_manifest required for building AOSP-Shamu properly

After you have cloned the AOSP repository, as per [these instructions](https://source.android.com/source/initializing.html), you must then clone this repository by entering the following instruction

```bash
git clone https://github.com/AOSP-Shamu/local_manifests .repo/local_manifests
```

Then you can go ahead and sync the source code again:

```bash
repo sync -j16
```

Happy building!