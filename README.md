# Alt Peek Privacy Policy

Last updated: September 6, 2026

Alt Peek is a browser extension that opens user-requested links and selected-text searches in an overlay without replacing the current page. This policy explains the information the extension handles, why it is needed, where it is sent, and how users can control it.

## Information Alt Peek Handles

Alt Peek handles only the information needed for its disclosed, user-facing features:

- **Web browsing activity:** the active tab hostname used to display the correct enabled or disabled icon state; open HTTP and HTTPS tab URLs briefly checked locally when the popup offers to refresh pages affected by an extension update; links the user chooses to preview, open, or copy; and the destination URL currently displayed in a preview.
- **User activity:** activation clicks or long presses, extension keyboard shortcuts, wheel gestures used for preview zoom or scrolling, and pointer coordinates used to place contextual controls. This interaction data is processed temporarily while the feature is used and is not retained or sent to developer-controlled servers.
- **Website content:** links under the pointer, text the user explicitly selects when selected-text search is enabled, and terms the user types into the in-preview find bar.
- **Extension settings:** theme, feature toggles, disabled hostnames, visual preferences, and other configuration choices.
- **Local interface state:** non-identifying timestamps, counters, and preferences used for optional interface details and the infrequent support reminder, such as the first day a preview was used, the number of preview openings up to the reminder threshold, settings-page decorative progress, the next eligible reminder time, and whether the user permanently disabled the reminder.

Alt Peek does not intentionally collect personally identifying information, health information, financial or payment information, authentication information, personal communications, precise location, form entries, passwords, or a complete browsing history.

## How Information Is Used

The information above is used only to provide features requested by the user, including:

- displaying a selected link or selected-text search inside the Alt Peek overlay;
- opening or copying a selected link;
- enabling or disabling Alt Peek for a hostname;
- positioning and operating preview controls;
- finding text locally inside the currently open preview after the user presses Ctrl+F;
- identifying open pages that need a one-time refresh after the extension is updated, only while the popup displays that refresh action; and
- applying and synchronizing the user's extension preferences.

Alt Peek does not send browsing data, interaction data, settings, or in-preview find terms to servers controlled by Alt Peek or Lanito Labs. The extension does not operate a developer-controlled data collection server.

## External Websites and Selected-Text Search

When the user opens a preview, the browser connects directly to the destination website. That website may receive information normally included in a web request, such as the requested URL, IP address, cookies, or other browser-provided information, according to that website's own privacy policy.

When the user activates selected-text search, the selected text is submitted directly to Google as a search query over HTTPS. This transfer occurs only after the user's explicit action and is subject to [Google's Privacy Policy](https://policies.google.com/privacy). Alt Peek and Lanito Labs do not receive the query.

For links to individual X posts, Alt Peek loads X's public embedded-post viewer at `platform.twitter.com` with X's do-not-track embed option enabled. The original post URL remains the address used by Alt Peek's open-in-new-tab and copy actions.

On X pages, Alt Peek briefly loads the current X URL in an invisible frame while its temporary X-domain-scoped header rule is active. This uses the existing browser session and sends no data to Alt Peek or Lanito Labs servers. The frame and its preparation rule are removed after four seconds. This prepares direct X previews to reuse the authenticated browser session.

The optional support page can open Stripe or Patreon in a separate browser tab after the user chooses a donation or membership option. Payment and membership information is handled directly by the selected provider under its own privacy policy and is not received or stored by Alt Peek or Lanito Labs. Copying the optional public cryptocurrency address does not transmit information to Alt Peek.

## Storage and Retention

Extension preferences and disabled hostnames are stored using Chrome's synchronized extension storage. Chrome may synchronize those preferences between browser profiles connected to the same Google account according to Chrome's synchronization and privacy settings.

Non-identifying interface state is stored using Chrome's local extension storage. The support reminder is first eligible after both seven days and ten preview openings. Choosing Not now postpones it for 30 days; opening support, choosing Already supported, or allowing the reminder to close automatically postpones it for 180 days. Users can disable future reminders until extension data is cleared or the extension is uninstalled.

Preview URLs, selected text, in-preview find terms, pointer coordinates, extension shortcut events, clicks, and wheel gestures are not retained by Alt Peek after the requested action. Stored settings remain until the user changes them, clears extension data, or uninstalls the extension, subject to Chrome's synchronization behavior.

## Sharing, Sale, Analytics, and Advertising

Alt Peek does not sell user data. It does not include analytics, telemetry, advertising trackers, behavioral profiling, or data used to determine creditworthiness or for lending purposes.

Information leaves the extension only when required for an explicit user-facing action: loading the destination website, submitting a user-activated selected-text query to Google, loading X content for an X preview, synchronizing settings through Chrome when browser sync is enabled, or opening Stripe or Patreon after the user chooses a support option. Alt Peek does not transfer user data to unrelated third parties.

## Security and Permissions

Alt Peek requests access to HTTP and HTTPS pages so its visible preview, link-copy, selected-text search, and per-site controls can work on supported websites. Network requests initiated by these features use HTTPS when the destination supports it.

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
