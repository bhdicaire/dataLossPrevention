# Channels

DLP Endpoints are available on desktop operating systems such as Apple macOS, Microsoft Windows. A few DLP vendors also support Chrome OS and Linux distributions. The current market share is available [here](https://gs.statcounter.com/os-market-share/desktop/worldwide).

An endpoint DLP monitor and prevent the unintentional or accidental sharing of sensitive information across several channels.
| Exfiltration activity | medium 
| :-- | :--: | 
|Copy a file| Bluetooth device |
|Copy a file| network share |
|Copy a file stored in an archived file format such as .zip| removable media |
|Print a file with sensitive information| local or network printer |
|Upload a file with sensitive information| local application such as Dropbox |
|Upload a file with sensitive information| web page via web browser |
|Copy sensitive information from an application and then paste it into another| restricted and unsanctioned applications |

A DLP policy action plan include:
 * Audit (e.g., log event)
 * Block (e.g., prevent data exfiltration)
 * Confirm (e.g., request a user confirmation including a justification)
 * Encrypt (e.g., prevent data exfiltration by encrypting sensitive content automatically)
 * Execute a local mitigation script
 * Notify (e.g., create a service desk case/ticket, send an alert to a security administrator on duty or to the user’s first line manager as defined in the directory information services such as Active Directory)

A DLP engine detect a policy match and take predefined action such as:
1. Log the event for auditing and reporting purposes
2. Log the event and notify the first line manager or a DLP administrator
3. Display a warning to the end user and log the event
4. Display a warning to the end user, request a confirmation including a justification, and log the event
5. Display a warning to the end user, request a confirmation, log the event, and notify
6. Prevent the exfiltration by blocking an email, copying or printing a file, and log the event
7. Prevent the exfiltration by blocking an email, copying or printing a file, log the event, and notify
8. Prevent the exfiltration by encrypting an email attachment, a file copied to a removable media or a network share, and log the event
9. Prevent the exfiltration by encrypting sensitive information, log the event, and notify

## Web Browsers

DLP endpoint supports the web browsers versions listed in the Vendor’s Certified Product Matrix.

The usual suspect and their current market share is available [here](https://gs.statcounter.com/browser-market-share).

DLP Endpoint monitor and/or enforce outbound content on the HTTP or HTTPS channel & web browser activities such as file access, copy/cut/paste, and screen capture operations.

To prevent possible compatibility issues, deploy only supported versions of web browsers and disable its auto-update feature. Every web browsers have auto-update enabled by default, so unsupported browsers may be installed on endpoint machines and bypass DLP monitoring or decrease the machine performance. Furthermore the DLP endpoint might be blind without any notification on the DLP console. 

Most DLP endpoints access web browser activities and outbound content via an extension. Usually, web browsers in _private browsing mode)_[^1] don’t load extensions to protect against potentially malicious extensions. It is recommended to disable it to prevent this option from being used to bypass DLP monitoring.

[^1]:Private browsing mode is also known as ephemeral, incognito mode or guest profile

Specific documentation related to Goggle Chrome and Mozilla Firefox are provided below. Most web browsers are based either on Chromium or Web kit.


### Apple Safari

[Safari](https://www.apple.com/safari/) is the default web browser on macOs, iPhone, and iPad. Apple no longer offers Safari for Windows. Proprietary extensions are available in Mac and iPhone & iPad [App Stores](itms-apps://safariExtensions). According to Apple, extensions that work in other web browsers can be [converted to support Safari](https://developer.apple.com/documentation/safariservices/safari_web_extensions/converting_a_web_extension_for_safari).

Apple Safari is based on [WebKit](https://webkit.org), an open-source browser project.

Some DLP vendors provide a Safari extension, and a mobile device management (MDM) tool is usually used to manage the web browser configuration in the Enterprise.
 
### Google Chrome

Google currently offer [five paths for Chrome updates](https://support.google.com/chrome/a/answer/9027636?hl=en&ref_topic=9023245): stable, extended stable, [beta](https://www.google.com/chrome/beta/), dev, and canary. Refer to the [Chrome Release Cycle](https://chromium.googlesource.com/chromium/src/+/master/docs/process/release_cycle.md) [Chrome update management strategies](https://support.google.com/chrome/a/answer/9982578?hl=en&ref_topic=9023245) and [managing extensions in your enterprise](https://support.google.com/chrome/a/answer/9296680) white papers for more information.

[Google Chrome](https://www.google.com/chrome/) is based on [chromium](https://www.chromium.org/Home/), an open-source browser project.

You can manage the web browser from a [cloud-based Admin console](https://support.google.com/chrome/a/answer/9116814), [a mobile device management (MDM) tool](https://support.google.com/chrome/a/answer/7550274), or via Windows Registry and [Active Directory (AD)](https://docs.microsoft.com/en-us/previous-versions/windows/desktop/Policy/group-policy-objects) or [Azure Active Directory Domain Services (Azure AD DS)](https://docs.microsoft.com/en-us/azure/active-directory-domain-services/manage-group-policy) Group Policy Object (GPO) as [documented by Google](https://support.google.com/chrome/a/answer/3115278).

On macOS, the [Google Software Update configuration file _com.google.Keystone.plist_](https://support.google.com/chrome/a/answer/7591084) applies to all Google apps installed including auto-updates setting.

On Linux, the [settings are defined](https://support.google.com/chrome/a/answer/9052345) in `/etc/default/google-chrome` and `/etc/opt/chrome/policies/managed/component_update.json`.

For information on the Chrome release schedule, see the [Chrome Releases Blog](https://chromereleases.googleblog.com/), the [chromium blog](https://blog.chromium.org/), and the release notes for [stable](https://support.google.com/chrome/a/answer/10314655) & [Long-term Support (LTS)](https://support.google.com/chrome/a/answer/12239814).

Refer to the [private browsing documentation](https://support.google.com/chrome/a/answer/9302896) for more information about the capabilities and the related policies. You can also force users to set up a Chrome Browser [managed profile](https://support.google.com/chrome/a/answer/11198768) when they sign in using their corporate Google Account on an unmanaged device. The policies and settings in the Google Admin console are applied _only_ to the managed profile including extensions.

### Mozilla Firefox

Mozilla currently offer [two paths for Firefox updates](https://support.mozilla.org/en-US/kb/choosing-firefox-update-channel): rapid release and Extended Support Release (ESR).

To turn off the Firefox rapid release auto-update, refer to the [knowledge base](https://support.mozilla.org/en-US/kb/how-stop-firefox-making-automatic-connections). 

The [Firefox Extended Support release (ESR)](https://www.mozilla.org/en-US/firefox/organizations/) is intended for organizations who deploy and maintain a desktop environment that don't automatically update when a new release is available.

For information on the Firefox release schedule, see the [roadmap](https://wiki.mozilla.org/Release_Management/Calendar) and the [release notes](https://www.mozilla.org/en-US/firefox/releases/).

Refer to the [Customizing Firefox using policies.json](https://support.mozilla.org/en-US/kb/customizing-firefox-using-policiesjson)and [Policy-templates README.md](https://github.com/mozilla/policy-templates/blob/master/README.md) to disable private browsing in Firefox.
