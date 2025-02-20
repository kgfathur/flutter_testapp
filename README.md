# notesapp

Notes App.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Debugging

```bash
# List devices
$ adb devices
List of devices attached
XXYYZZ123     device

# Sample command to List app data dir  
$ adb -s XXYYZZ123 shell run-as net.cloudtechie.notesapp ls -lh /data/data/net.cloudtechie.notesapp

# Or interactively
$ adb -s XXYYZZ123 shell

# inside adb shell
$ run-as net.cloudtechie.notesapp

# Sample
m1xx:/ $ run-as net.cloudtechie.notesapp
m1xx:/data/user/0/net.cloudtechie.notesapp $ pwd
/data/user/0/net.cloudtechie.notesapp
m1xx:/data/user/0/net.cloudtechie.notesapp $ ls -lh
total 18K
drwxrwx--x 3 u0_a432 u0_a432       3.3K 2024-12-29 14:11 app_flutter
drwxrws--x 2 u0_a432 u0_a432_cache 3.3K 2024-12-29 13:37 cache
drwxrws--x 4 u0_a432 u0_a432_cache 3.3K 2024-12-29 14:11 code_cache
drwxrwx--x 2 u0_a432 u0_a432       3.3K 2024-12-29 13:47 databases
drwxrwx--x 2 u0_a432 u0_a432       3.3K 2024-12-29 14:11 files
drwxrwx--x 2 u0_a432 u0_a432       3.3K 2024-12-29 14:11 shared_prefs
m14x:/data/user/0/net.cloudtechie.notesapp $
```
