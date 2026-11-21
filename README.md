# Alt Peek Privacy Policy

Last updated: November 21, 2026

Alt Peek is a browser extension that opens user-requested links and selected-text searches in an overlay and can copy explicitly selected text without replacing the current page. This policy explains the information the extension handles, why it is needed, where it is sent, and how users can control it.

## Information Alt Peek Handles

Alt Peek handles only the information needed for its disclosed, user-facing features:

- **Web browsing activity:** the active tab hostname used to display the correct enabled or disabled icon state; open HTTP and HTTPS tab URLs briefly checked locally when the popup offers to refresh pages affected by an extension update; links the user chooses to preview, open, or copy; and the destination URL currently displayed in a preview.
- **User activity:** activation clicks or long presses, extension keyboard shortcuts, wheel gestures used for preview zoom or scrolling, and pointer coordinates used to place contextual controls. This interaction data is processed temporarily while the feature is used and is not retained or sent to developer-controlled servers.
- **Website content:** links under the pointer, text the user explicitly selects when selected-text actions are enabled (including selections in supported text fields and editors, but not password fields), and terms the user types into the in-preview find bar.
- **Clipboard content (optional):** plain text is checked locally while a supported editable field is focused after the user enables Paste. When the user activates Paste, the extension reads the current clipboard content again. In the default formatted mode, it may also read clipboard HTML for a supported rich-text editor. Clipboard contents are not stored or sent by Alt Peek.
- **Extension settings:** theme, feature toggles, disabled hostnames, visual preferences, and other configuration choices.
- **Local interface state:** non-identifying timestamps, counters, and preferences used for optional interface details and the infrequent support reminder, such as the first day a preview was used, the number of preview openings up to the reminder threshold, settings-page decorative progress, the next eligible reminder time, and whether the user permanently disabled the reminder.

Alt Peek does not automatically collect form entries, passwords, a complete browsing history, or personal information for the developer. Text explicitly selected by the user and text read locally by the optional Paste feature could contain personal or sensitive information. Password fields are not supported. Selected text is sent to Google only when the user activates Search; Copy writes it to the local clipboard. Clipboard text read for Paste is never retained or transmitted by Alt Peek.

## How Information Is Used

The information above is used only to provide features requested by the user, including:

- displaying a selected link or selected-text search inside the Alt Peek overlay;
- copying explicitly selected text after the user activates the visible copy action;
- showing an optional Paste button only when the user has enabled it, a supported editable field is focused, and clipboard text is available; the clipboard is checked locally, and text is inserted only after the user activates Paste;
- opening or copying a selected link;
- enabling or disabling Alt Peek for a hostname;
- positioning and operating preview controls;
- finding text locally inside the currently open preview after the user presses Ctrl+F;
- identifying open pages that need a one-time refresh after the extension is updated, only while the popup displays that refresh action; and
- applying and synchronizing the user's extension preferences.

Alt Peek does not send browsing data, interaction data, settings, or in-preview find terms to servers controlled by Alt Peek or Lanito Labs. The extension does not operate a developer-controlled data collection server.

## External Websites and Selected-Text Actions

When the user opens a preview, the browser connects directly to the destination website. That website may receive information normally included in a web request, such as the requested URL, IP address, cookies, or other browser-provided information, according to that website's own privacy policy.

When the user activates selected-text search, the selected text is submitted directly to Google as a search query over HTTPS. This transfer occurs only after the user's explicit action and is subject to [Google's Privacy Policy](https://policies.google.com/privacy). Alt Peek and Lanito Labs do not receive the query.

When the user activates the Copy selected text action, the text is written only to the local clipboard. It is not sent to Google, Alt Peek, Lanito Labs, or another external service.

When the user enables the optional Paste button, Alt Peek requests Chrome's optional `clipboardRead` permission. While a supported editable field is focused, the extension reads plain clipboard text locally to determine whether to show the button. After the user activates Paste, it reads the clipboard again. By default, it also reads HTML when a rich-text editor supports formatted paste, then filters the HTML before inserting it; the user can instead choose plain-text paste. Standard text inputs receive plain text. The extension does not keep a clipboard history, store clipboard contents, or transmit them to any service. The feature excludes password fields and may be unavailable in browser or page contexts where clipboard reading is restricted.

For links to individual X posts, Alt Peek loads X's public embedded-post viewer at `platform.twitter.com` with X's do-not-track embed option enabled. The original post URL remains the address used by Alt Peek's open-in-new-tab and copy actions.

On X pages, Alt Peek briefly loads the current X URL in an invisible frame while its temporary X-domain-scoped header rule is active. This uses the existing browser session and sends no data to Alt Peek or Lanito Labs servers. The frame and its preparation rule are removed after four seconds. This prepares direct X previews to reuse the authenticated browser session.

The optional support page can open Stripe, PayPal, or Patreon in a separate browser tab after the user chooses a donation or membership option. Payment and membership information is handled directly by the selected provider under its own privacy policy and is not received or stored by Alt Peek or Lanito Labs. Copying the optional public cryptocurrency address does not transmit information to Alt Peek.

## Storage and Retention

Extension preferences and disabled hostnames are stored using Chrome's synchronized extension storage. Chrome may synchronize those preferences between browser profiles connected to the same Google account according to Chrome's synchronization and privacy settings.

Non-identifying interface state is stored using Chrome's local extension storage. The support reminder is first eligible after both seven days and ten preview openings. Choosing Not now postpones it for 30 days; opening support, choosing Already supported, or allowing the reminder to close automatically postpones it for 180 days. Users can disable future reminders until extension data is cleared or the extension is uninstalled.

Preview URLs, selected text, clipboard contents, in-preview find terms, pointer coordinates, extension shortcut events, clicks, and wheel gestures are not retained by Alt Peek after the requested action. The Paste feature's enabled preference is stored locally. Its optional clipboard permission can be revoked in Chrome's extension settings or by turning the feature off. Other stored settings remain until the user changes them, clears extension data, or uninstalls the extension, subject to Chrome's synchronization behavior.

## Sharing, Sale, Analytics, and Advertising

Alt Peek does not sell user data. It does not include analytics, telemetry, advertising trackers, behavioral profiling, or data used to determine creditworthiness or for lending purposes.

Information leaves the extension only when required for an explicit user-facing action: loading the destination website, submitting a user-activated selected-text query to Google, loading X content for an X preview, synchronizing settings through Chrome when browser sync is enabled, or opening Stripe, PayPal, or Patreon after the user chooses a support option. Copying selected text and reading clipboard text for the optional Paste feature remain local. Alt Peek does not transfer user data to unrelated third parties.

## Security and Permissions

Alt Peek requests access to HTTP and HTTPS pages so its visible preview, link-copy, selected-text search and copy actions, optional Paste button, and per-site controls can work on supported websites. The `clipboardRead` permission is optional and requested only when the user enables the Paste button in settings; Chrome displays its permission warning. The feature can be disabled later, which also removes the optional permission. Network requests initiated by these features use HTTPS when the destination supports it.

The extension uses temporary browser rules while a preview is active to permit compatible websites to appear inside the user-requested preview. Regular preview rules are scoped to the source tab. X preview rules are restricted to requests for `x.com` and `twitter.com`, but can match those requests in other tabs while an X preview or its four-second preparation is active. Each rule is removed when the preview closes, the preparation finishes, or its source tab navigates.

Alt Peek does not execute remotely hosted code.

## User Control and Deletion

Users can disable individual features, disable Alt Peek on specific hostnames, clear the disabled-host list, clear extension data through Chrome, or uninstall the extension at any time. Clearing or uninstalling synchronized data may also depend on Chrome's synchronization settings.

## Chrome Web Store Limited Use

Alt Peek's use and transfer of information received from Chrome APIs adheres to the Chrome Web Store User Data Policy, including its Limited Use requirements. Information is used only to provide or improve the extension's disclosed, user-facing features. It is not used or transferred for personalized advertising, unrelated purposes, creditworthiness, or lending.

## Changes to This Policy

This policy may be updated when Alt Peek's features or data practices change. The date at the top identifies the latest revision. Material changes will be disclosed through the extension or its Chrome Web Store listing when required.

## Contact

Questions about this policy can be sent to [lanitolabs@gmail.com](mailto:lanitolabs@gmail.com).
