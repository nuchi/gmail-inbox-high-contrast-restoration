# Gmail Inbox High-Contrast Restoration

This purely cosmetic filter list for uBlock Origin restores the high-contrast Gmail Inbox themes from pre-2022. It restores colors and sizes to their former high-contrast selves, and gets rid of the new low-contrast hard-to-read colors. Assorted other changes include restoring the Compose button color, restoring the default and high-contrast themes to their original colors, and restoring curved button radiuses to be approximately as round as they used to be.

[Subscribe to the list (requires uBlock Origin)](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/nuchi/gmail-inbox-high-contrast-restoration/master/gmail-high-contrast-restoration.txt&title=Gmail%20Inbox%20High-Contrast%20Restoration)

**NOTE:** a page refresh is sometimes required when switching themes. If the colors look weird, please refresh the page.

Tested with Firefox on macos.

## Frequently Asked Questions

### The subscribe link above doesn't work, how do I fix it?

This can happen if uBlock Origin isn't installed. It can also happen if another adblocker is installed and is interfering with uBO's ability to handle the subscribe link. Make sure uBlock Origin is installed, and disable all other adblockers, then try the link again. (You can re-enable the other adblockers afterwards, although uBO works best if it's the only adblocker active.)

### Some fonts don't work or appear weird, or unread emails aren't bolded, how do I fix it?

This can happen on some older browsers. Make sure you're using an up-to-date Firefox or Chrome. Unfortunately I can't support older browsers or forks of Firefox/Chrome.

### How do I uninstall it?

Go to the uBO dashboard, "Filter lists" tab, then scroll to the bottom ("Custom" section). Then uncheck or delete "Gmail Inbox High-Contrast Restoration" and click the "Apply Changes" button at the top.

### How do I get rid of the sidebar with "Chat", "Spaces", "Meet"?

This can actually be done from GMail settings, without needing to use this filter list: click the gear icon in the top right corner, then "Apps in Gmail" > "Chat and Meet" > "Customize", then uncheck Google Chat and Google Meet.

### How do I move chat back under the "Inbox", "Sent", etc sidebar?

Unfortunately this is not possible with this filter list.

### I'm using an up-to-date version of Firefox or Chrome, and the filter list is partially working, but something else appears wrong, how do I fix it?

If the filter list is partially working (a good way to check that the list is working is that the "Compose" button is red), and you're using an up-to-date version of Firefox or Chrome, and something else appears wrong, please [search the issues](https://github.com/nuchi/gmail-inbox-high-contrast-restoration/issues) to see if it's a known bug. If it's not, please open a new issue describing the problem.
