# Stylo releases

Downloads for **Stylo**, a lightweight markdown editor for Windows with live preview.

## Install

Open the [latest release](https://github.com/XarhsSta/stylo-releases/releases/latest), download
`Stylo_X.Y.Z_x64-setup.exe` and run it. The `.msi` installs the same app, for deploying with
Windows tools.

The installers are not code-signed, so on first run Windows SmartScreen shows
*"Windows protected your PC"*. Click **More info**, then **Run anyway**.

## Updates

Once installed, Stylo checks this repository for new versions on startup (and from
Settings → General → Check now) and offers to install them. Each release carries a
`latest.json`, signed with Stylo's update key, which is what the app reads.

## About this repository

It holds releases only. The source code lives in a private repository, whose release workflow
publishes every version here.
