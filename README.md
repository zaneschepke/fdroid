# fdroid
This repository hosts an [F-Droid](https://f-droid.org/) repo for my apps. This allows you to install and update apps very easily.

### Apps

<!-- This table is auto-generated. Do not edit -->
| Icon | Name | Description | Version |
| --- | --- | --- | --- |
| <a href="https://github.com/zaneschepke/wgtunnel"><img src="fdroid/repo/icons/" alt="WG Tunnel icon" width="36px" height="36px"></a> | [**WG Tunnel**](https://github.com/zaneschepke/wgtunnel) | An alternative Android client app for WireGuard VPN | 3.3.8 (33800) |
<!-- end apps table -->

### How to use
1. At first, you should [install the F-Droid app](https://f-droid.org/), it's an alternative app store for Android.
2. Now you can copy the following [link](https://raw.githubusercontent.com/zaneschepke/fdroid/main/fdroid/repo?fingerprint=0890C5D44C0109E366801C39840325E810E21B270B9D2AEC53CE0D6C5FC849DB), then add this repository to your F-Droid client:

    ```
    https://raw.githubusercontent.com/zaneschepke/fdroid/main/fdroid/repo?fingerprint=0890C5D44C0109E366801C39840325E810E21B270B9D2AEC53CE0D6C5FC849DB
    ```

    Alternatively, you can also scan this QR code:

    <p align="center">
      <img src=".github/qrcode.png?raw=true" alt="F-Droid repo QR code"/>
    </p>

3. Open the link in F-Droid. It will ask you to add the repository. Everything should already be filled in correctly, so just press "OK".
4. You can now install my apps, e.g. start by searching for "Notality" in the F-Droid client.

Please note that some apps published here might contain [Anti-Features](https://f-droid.org/en/docs/Anti-Features/). If you can't find an app by searching for it, you can go to settings and enable "Include anti-feature apps".

### For developers
If you are a developer and want to publish your own apps right from GitHub Actions as an F-Droid repo, you can fork/copy this repo and see  [the documentation](setup.md) for more information on how to set it up.

### [License](LICENSE)
The license is for the files in this repository, *except* those in the `fdroid` directory. These files *might* be licensed differently; you can use an F-Droid client to get the details for each app.
