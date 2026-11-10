# Lahjah Web

This repository contains the generated static web build of Lahjah. It does not
include the Flutter source project.

The site is configured for the repository root and is published with GitHub
Pages. To rebuild it from the Flutter project, use Flutter 3.47.9 / Dart 3.13.7
and run:

```sh
flutter pub get
flutter build web --base-href /lahjah-web/
```

Replace the contents of this repository with the generated `build/web/` files
and push to the `main` branch to publish updates.
