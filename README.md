# bugbook_mobile_flutter

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

```
https://developer.android.com/studio#command-tools ---> commandlinetools-linux-13114758_latest.zip
mkdir -p ~/Android/Sdk/cmdline-tools/latest
unzip commandlinetools-linux-13114758_latest.zip -d ~/Android/Sdk/cmdline-tools/latest
~/Android/Sdk/cmdline-tools/latest
mv ~/Android/Sdk/cmdline-tools/latest/cmdline-tools/* ~/Android/Sdk/cmdline-tools/latest/
rm -rf ~/Android/Sdk/cmdline-tools/latest/cmdline-tools
~/Android/Sdk/cmdline-tools/latest/bin/sdkmanager --install "cmdline-tools;latest"

~/Android/Sdk/cmdline-tools/latest/bin/sdkmanager --install "cmdline-tools;latest"
flutter doctor --android-licenses
flutter doctor
sudo apt update
sudo apt install clang cmake ninja-build libgtk-3-dev
flutter doctor
sudo ln -s /path/to/android-studio/bin/studio.sh /usr/local/bin/android-studio
flutter doctor
export ANDROID_HOME=$HOME/Android/Sdk
export PATH=$ANDROID_HOME/emulator:$ANDROID_HOME/tools:$ANDROID_HOME/tools/bin:$ANDROID_HOME/platform-tools:$PATH
source ~/.bashrc
flutter doctor -v
sudo rm -rf /opt/android-studio
flutter doctor
emulator -list-avds
flutter devices
flutter run -d emulator-5554


```
