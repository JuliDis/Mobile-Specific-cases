# Basic Checks for Mobile Application Testing

## Functional Testing

At this point, it is important for us to make sure that our product meets the desired functional specification mentioned in the development documentation.

- Installation / removal / rolling versions;
- Launching the application (displaying the Splash Screen);
- The performance of the main functionality of the application;
- Authorization (by phone number/via social networks/e-mail);
- Registration (by phone number/via social networks/e-mail);
- Onboarding new users;
- Validation of required fields;
- Navigation between sections of the application;
- Editing data in the user profile;
- Verification of payment;
- Filter testing;
- Bonuses;
- Correct display of errors;
- Working with files (sending/receiving/viewing);
- Testing timeouts;
- Testing stubs (no internet connection / no, for example, goods, etc.);
- Testing pop-ups, alerts;
- WebView testing;
- Scroll/swipe elements;
- Testing PUSH notifications;
- Folding/expanding the application;
- Different types of connections (cellular / Wi-Fi);
- Screen orientation (landscape/portrait);
- Dark/light themes;
- Advertising in the application;
- Sharing content on social media networks;
- Work application in the background;
- Pagination of pages;
- Privacy Policy and other references to documents.

## Compatibility Testing

Compatibility testing is used to ensure that your app is compatible with other OS versions, different skins and third party services, and device hardware.

- Correct display of geo;
- Information about transactions (checks, etc.);
- Various payment methods (Google Pay, Apple Pay);
- Testing sensors (illuminance, device temperature, gyroscope, etc.);
- Testing interruptions (incoming call/sms/push/alarm clock/do not disturb mode, etc.);
- Connecting external devices (memory card/headphones, etc.).

## Security testing

This test is aimed at finding flaws and gaps in terms of application security.

- Testing permissions (access to camera/microphone/gallery/etc.);
- User data (passwords) are not transmitted in clear text;
- In the fields with password entry and password confirmation, the data is hidden by asterisks.

## Localization and globalization testing

Application internationalization/globalization testing involves testing the application for various locations, date formats, numbers, and currencies, and replacing actual strings with pseudo-strings. Localization testing involves testing the application with localized strings, images, and workflows for a specific region.

- All elements in the application are translated into the appropriate language;
- Texts are protected inside the application and the user can set the required language in the application settings;
- Texts depend on the language in the system settings;
- Texts come from the server;
- Correct display of date formats (YEAR - MONTH - DAY or DAY - MONTH - YEAR.);
- Correct display of time depending on the time zone.

## Usability Testing

Usability testing helps to ensure that the user can easily and efficiently use the product in order to achieve their goals. In other words, this is nothing more than testing the friendliness of the application for the user.

- Correct display of elements on devices with different screen resolutions;
- All fonts meet the requirements;
- All texts are correctly aligned;
- All error messages are correct, without spelling and grammatical errors;
- Correct screen titles;
- There are placeholders in the search strings;
- Inactive elements are displayed in gray;
- Links to documents lead to the corresponding section on the site;
- Animation between transitions;
- Correct return to the previous screen;
- Supports basic gestures when working with touch screens (swipe back, etc.);
- Pixel perfect.

## Stress Testing

Stress testing aims to determine the effectiveness of an application's performance under heavy load conditions. The stress test in this context is only focused on mobile devices.

- High CPU usage;
- Lack of memory;
- Battery loading;
- Failures;
- Low network bandwidth;
- A large number of user interactions with the application (this may require simulating real network conditions).

## Cross-platform testing

An important type of testing that needs to be done to understand whether the product under test will properly display on the various platforms used by the target audience.

- The performance of the application on various devices from different manufacturers.

## Benchmarking

If a user installs an app and it doesn't show up quickly enough (for example, within three seconds), it may be removed in favor of another app. Time and resource consumption aspects are important success factors for an application, and performance testing is done to measure these aspects.

- Application loading time;
- Query Processing;
- Data caching;
- Application resource consumption (e.g. battery consumption).
