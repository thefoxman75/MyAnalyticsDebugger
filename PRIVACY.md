# Privacy Policy for My Analytics Debugger

**Effective date:** November 2, 2026

My Analytics Debugger ("MAD") is a browser developer-tools extension for inspecting Adobe Web SDK and Classic Adobe Analytics requests. This policy explains what information MAD processes, how it is used, and how it is protected.

## Information MAD processes

When Chrome or Microsoft Edge DevTools is open, MAD uses the browser's DevTools APIs to inspect network requests from the tab being actively inspected. MAD limits its request processing to Adobe Web SDK and Classic Adobe Analytics requests needed to provide its debugging features.

The information made available through those requests may include:

- request URLs, methods, query parameters, headers, and payload data;
- XDM fields, Classic Adobe Analytics variables, event data, and identifiers included by the inspected website;
- page URLs and other browsing or page-related information contained in analytics requests; and
- limited tag-management metadata, such as the detected tag manager, property, environment, and build information.

The exact contents are controlled by the website being inspected. Analytics requests may contain identifiers or other information that the website has chosen to include.

## How the information is used

MAD uses this information only to provide its user-facing debugging features, including displaying, organizing, filtering, highlighting, flattening, and exporting analytics request data.

Request data is processed locally within the browser. MAD does not transmit analytics requests, browsing activity, page data, or request contents to the developer or to any external server.

## Information stored locally

MAD uses `chrome.storage.local` to save extension preferences on the user's device. These preferences may include:

- display and appearance settings;
- request-type colors and title-field settings;
- selected fields and filter configuration;
- recent filter terms; and
- expand, collapse, and table-width preferences.

MAD does not use these settings for tracking or advertising. Locally stored preferences remain until the user clears them, removes the extension, or clears the extension's browser storage.

Analytics request data shown in the MAD DevTools panel is held only for the active DevTools session and is not saved by MAD as persistent extension storage.

## Exports

MAD allows users to export displayed debugging information. An export occurs only when initiated by the user and is saved through the browser to a location controlled by the user. MAD does not upload or receive exported files.

## Sharing and sale of information

MAD does not sell, rent, share, or transfer user data to third parties. MAD contains no advertising, analytics, tracking pixels, or remote telemetry.

## Permissions

MAD requests the `storage` permission solely to retain the local preferences described above. It does not request host permissions, access to browsing history, or unlimited storage.

## Data security

MAD minimizes data access by operating only while DevTools is open and by processing relevant analytics requests locally. Because request data can reflect information supplied by the inspected website, users should take care when exporting or sharing debugging output.

## Chrome Web Store Limited Use disclosure

MAD's use of information received from browser APIs adheres to the Chrome Web Store User Data Policy, including the Limited Use requirements. Information is used only to provide and improve MAD's single-purpose analytics-debugging functionality. It is not used for advertising, profiling, creditworthiness, or any unrelated purpose, and is not made available for human review by the developer.

## Children's privacy

MAD is a developer tool and is not directed to children. It does not knowingly collect personal information from children.

## Changes to this policy

This policy may be updated if MAD's functionality or data practices change. Material changes will be reflected by revising the effective date and publishing the updated policy with the extension's project materials.

## Contact

Questions or concerns about this policy may be submitted through the project's GitHub issue tracker:

<https://github.com/thefoxman75/MyAnalyticsDebugger/issues>

