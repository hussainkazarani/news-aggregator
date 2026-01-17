# TrendView

**A Personalized News Aggregator**

## Overview

TrendView is a news aggregation app designed to provide users with personalized, real-time news updates from a variety of sources using the Perigon.io API. The app offers features such as browsing categorized sections, saving favorite articles, and following specific sources to stay updated on topics of interest.

## Features

-   **Breaking News**: Get the latest headlines instantly.
-   **Categorized Sections**: Explore news based on topics of interest.
-   **Bookmarks**: Save articles to read later.
-   **Source Following**: Follow specific news outlets for tailored content.
-   **Search Functionality**: Find articles or topics effortlessly.
-   **WebView Integration**: View full articles within the app.

The app is built using **Flutter** with state management handled through **Provider**, ensuring a smooth and responsive user experience.

## Demo

|                    **Failed Verification**                     |                    **Success Verification**                    |                          **Search**                          |
| :------------------------------------------------------------: | :------------------------------------------------------------: | :----------------------------------------------------------: |
| <img src="assets/github_images/veri_failed.webp" width="230"/> | <img src="assets/github_images/veri_succes.webp" width="230"/> | <img src="assets/github_images/searching.webp" width="230"/> |

|                        **Bookmarks**                         |                        **WebView**                         |
| :----------------------------------------------------------: | :--------------------------------------------------------: |
| <img src="assets/github_images/bookmarks.webp" width="230"/> | <img src="assets/github_images/webview.webp" width="230"/> |

## Installation and Usage (End Users)

### Prerequisites

-   **Flutter SDK** (version 3.0 or above)
-   Android/iOS Emulator or Physical Device
-   (iOS only) macOS + Xcode + CocoaPods installed

### Installation

1. **API Key Setup**

    - Create an account on [Perigon.io](https://perigon.io) to generate an API key.
    - Open the existing `.env` file in the project root.
    - Add your API key like this:
        ```env
        PERIGON_API_KEY=YOUR_API_KEY_HERE
        ```

2. **Clone the Repository**

        ```bash
        git clone https://github.com/hussainkazarani/news-aggregator.git
        cd news-aggregator
        ```

3. **Install Dependencies**

    ```bash
    flutter pub get
    ```

4. **Run the App**
    ### iOS
    ```bash
    cd ios
    pod install
    cd ..
    flutter run
    ```
    ### Android
    ```bash
    flutter run
    ```
