# aapt

> Android Asset Packaging Tool 2: compile and package an Android app's resources.
> More information: <https://developer.android.com/tools/aapt2>.

- List the contents of the APK's resource table:

`aapt2 dump resources {{path/to/app.apk}}`

- Compile the resources in a directory to an [o]utput directory [v]erbosely:

`aapt2 compile --dir {{path/to/input_resources}} -o {{path/to/output_resource_dir}} -v`

- [v]erbosely link specific compiled resources and a manifest file, providing an `android.jar` ([I]), into an output APK file:

`aapt2 link -v -I {{path/to/android.jar}} {{compiled_resource1 compiled_resource2 ...}} --manifest /path/to/AndroidManifest.xml -o output.apk`
