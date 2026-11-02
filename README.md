

![MMAS: Money Tracker](https://user-images.githubusercontent.com/72301141/206877824-90492e92-2e2d-4de6-b23c-312f283bdfd6.png)

# Money Tracker App

**Track every expense and income in seconds, then see where your money goes.**  

A free, ad-free personal finance app built with Flutter.

![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)




---

## Contents

- [About](#about)
- [Features](#features)
- [How it works](#how-it-works)
- [Screenshots](#screenshots)
- [Getting started](#getting-started)
- [Project structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## About

MMAS helps you manage money, track spending and work toward your financial goals in one place. Enter your expenses and income, assign each to a category, and MMAS takes care of the rest. Tracking should never feel like another chore.

The app is free, shows no ads and has no feature restrictions. It does not rely on third-party servers.

## Features

| | |
|---|---|
| **Expenses and income** | Record spending and earnings in a few taps. |
| **Unlimited categories** | Start with the preset categories or build your own budgeting system, as detailed as you like. |
| **Reports for any period** | Daily, weekly, monthly, quarterly, yearly and all-time views. |
| **Charts** | See your spending as charts instead of a list of numbers. |
| **Free and private** | No ads, no paywalled features, no third-party servers. |

## How it works

|                                           |                                                             |                                                                          |
| ----------------------------------------- | ----------------------------------------------------------- | ------------------------------------------------------------------------ |
| **1. Add** Enter an expense or an income. | **2. Categorise** Assign it to a preset or custom category. | **3. Review** Open a report for any period and see where the money went. |

## Screenshots

|                                                                                                                             |                                                                                                                             |                                                                                                                             |
| --------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| ![MMAS screenshot 1](https://user-images.githubusercontent.com/72301141/206411105-4a64ada8-2a9c-4804-ad59-59302a6a82c5.jpg) | ![MMAS screenshot 2](https://user-images.githubusercontent.com/72301141/206417378-9da25e84-bf21-401c-bf23-bce3b352311e.jpg) | ![MMAS screenshot 3](https://user-images.githubusercontent.com/72301141/206417548-787625af-f4b1-4c9d-8aac-fa9bd7c47bfb.jpg) |
| ![MMAS screenshot 4](https://user-images.githubusercontent.com/72301141/206417565-01bc0f8c-27a4-4648-a845-0a7c29a957c2.jpg) | ![MMAS screenshot 5](https://user-images.githubusercontent.com/72301141/206417707-be626efa-6bed-41be-a932-4e7a5aa22039.jpg) | ![MMAS screenshot 6](https://user-images.githubusercontent.com/72301141/206417743-8a51d828-efe0-4d3e-9f6b-5b16a4f3b086.jpg) |
| ![MMAS screenshot 7](https://user-images.githubusercontent.com/72301141/206417756-a979fefe-23f8-4a21-bfa5-7e45745c19f0.jpg) | ![MMAS screenshot 8](https://user-images.githubusercontent.com/72301141/206417834-25dc5bb4-c099-4d90-81a6-eb4e469bc40e.jpg) | ![MMAS screenshot 9](https://user-images.githubusercontent.com/72301141/206417851-2ee18113-04bf-48ae-bf83-d377b4517742.jpg) |

## Getting started

### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (run `flutter doctor` to confirm your setup)
- Xcode for iOS builds, or Android Studio for Android builds

### Run it locally

```bash
# 1. Clone the repository
git clone https://github.com/floranguyen0/mmas-money-tracker.git
cd mmas-money-tracker

# 2. Install dependencies
flutter pub get

# 3. Run on a connected device or emulator
flutter run
```

To run the tests:

```bash
flutter test
```



## Project structure

```text
mmas-money-tracker/
├── android/     # Android platform project
├── ios/         # iOS platform project
├── images/      # Image assets
├── lib/         # Dart source code
├── test/        # Tests
├── pubspec.yaml # Dependencies and assets
└── LICENSE
```

## Contributing

Issues and pull requests are welcome. If you plan a larger change, open an issue first so we can talk it through. Before sending a pull request, run `flutter analyze` and `flutter test`.

If MMAS is useful to you, a star on the repository helps others find it.

## License

MMAS: Money Tracker is [MIT-licensed](LICENSE).