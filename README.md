# chrome-extension-samples
pffy's COPY-ONLY git mirror of Google Chrome extension samples

# LICENSE
  + READ THIS BSD-STYLE [LICENSE](https://raw.githubusercontent.com/pffy/chrome-extension-samples/master/LICENSE.md).
  + **This is not Pffy's usual UNLICENSE.**
  + This is Google's LICENSE.

# SUMMARY

  + This is a "convenience" git repo to help us download a copy of
  all the chrome extension on virtual machines.
  + There is no detailed documentation here. That's a different repo.
  + There is a summary of all the **chrome.* API** calls.
  + There is also a summary of all the 91 available of the 92 total
  sample extensions.

## CALLS

The following is a list of **chrome.* API** calls made in the extension samples.

  + alarms.onAlarm
  + alarms.create
  + alarms.get
  + bookmarks.onChanged
  + bookmarks.onCreated
  + bookmarks.onMoved
  + bookmarks.onRemoved
  + bookmarks.create
  + bookmarks.getChildren
  + bookmarks.getTree
  + bookmarks.move
  + bookmarks.remove
  + bookmarks.removeTree
  + bookmarks.update
  + browserAction.onClicked
  + browserAction.setBadgeBackgroundColor
  + browserAction.setBadgeText
  + browserAction.setIcon
  + browserAction.setTitle
  + browsingData.remove
  + commands.onCommand
  + contentSettings.ContentSetting.clear
  + contentSettings.ContentSetting.get
  + contentSettings.ContentSetting.getResourceIdentifiers
  + contentSettings.ContentSetting.set
  + contentSettings.plugins
  + contextMenus.onClicked
  + contextMenus.create
  + cookies.onChanged
  + cookies.getAll
  + cookies.remove
  + debugger.onDetach
  + debugger.onEvent
  + debugger.attach
  + debugger.detach
  + debugger.sendCommand
  + declarativeContent.PageStateMatcher
  + declarativeContent.ShowPageAction
  + declarativeWebRequest.IgnoreRules
  + declarativeWebRequest.RedirectRequest
  + declarativeWebRequest.RequestMatcher
  + desktopCapture.cancelChooseDesktopMedia
  + desktopCapture.chooseDesktopMedia
  + devtools.inspectedWindow.eval
  + devtools.inspectedWindow.reload
  + devtools.network.onRequestFinished
  + devtools.network.getHAR
  + devtools.panels.ElementsPanel.onSelectionChanged
  + devtools.panels.create
  + devtools.panels.ElementsPanel.createSidebarPane
  + documentScan.scan
  + downloads.onChanged
  + downloads.onCreated
  + downloads.onDeterminingFilename
  + downloads.onErased
  + downloads.acceptDanger
  + downloads.cancel
  + downloads.download
  + downloads.drag
  + downloads.erase
  + downloads.getFileIcon
  + downloads.open
  + downloads.pause
  + downloads.removeFile
  + downloads.resume
  + downloads.search
  + downloads.setShelfEnabled
  + downloads.show
  + downloads.showDefaultFolder
  + experimental.devtools.audits.addCategory
  + extension.onRequest
  + extension.getBackgroundPage
  + extension.getURL
  + extension.getViews
  + extension.isAllowedFileSchemeAccess
  + extension.isAllowedIncognitoAccess
  + extension.sendRequest
  + extension.lastError
  + fileSystemProvider.onCloseFileRequested
  + fileSystemProvider.onGetMetadataRequested
  + fileSystemProvider.onOpenFileRequested
  + fileSystemProvider.onReadDirectoryRequested
  + fileSystemProvider.onReadFileRequested
  + fileSystemProvider.onUnmountRequested
  + fileSystemProvider.mount
  + fileSystemProvider.unmount
  + fontSettings.onDefaultFixedFontSizeChanged
  + fontSettings.onDefaultFontSizeChanged
  + fontSettings.onFontChanged
  + fontSettings.onMinimumFontSizeChanged
  + fontSettings.clearDefaultFixedFontSize
  + fontSettings.clearDefaultFontSize
  + fontSettings.clearFont
  + fontSettings.clearMinimumFontSize
  + fontSettings.getDefaultFixedFontSize
  + fontSettings.getDefaultFontSize
  + fontSettings.getFont
  + fontSettings.getFontList
  + fontSettings.getMinimumFontSize
  + fontSettings.setDefaultFixedFontSize
  + fontSettings.setDefaultFontSize
  + fontSettings.setFont
  + fontSettings.setMinimumFontSize
  + history.getVisits
  + history.search
  + i18n.getAcceptLanguages
  + i18n.getMessage
  + idle.onStateChanged
  + idle.queryState
  + input.ime.onActivate
  + input.ime.onBlur
  + input.ime.onDeactivated
  + input.ime.onFocus
  + input.ime.onKeyEvent
  + input.ime.commitText
  + management.getAll
  + management.launchApp
  + management.uninstallSelf
  + notifications.onButtonClicked
  + notifications.onClicked
  + notifications.clear
  + notifications.create
  + omnibox.onInputCancelled
  + omnibox.onInputChanged
  + omnibox.onInputEntered
  + omnibox.onInputStarted
  + omnibox.setDefaultSuggestion
  + pageAction.onClicked
  + pageAction.hide
  + pageAction.setIcon
  + pageAction.setTitle
  + pageAction.show
  + permissions.onAdded
  + permissions.onRemoved
  + permissions.contains
  + permissions.remove
  + permissions.request
  + power.releaseKeepAwake
  + power.requestKeepAwake
  + processes.onUpdatedWithMemory
  + processes.getProcessIdForTab
  + processes.terminate
  + proxy.onProxyError
  + runtime.onConnect
  + runtime.onInstalled
  + runtime.onMessage
  + runtime.onStartup
  + runtime.onSuspend
  + runtime.connect
  + runtime.connectNative
  + runtime.getURL
  + runtime.sendMessage
  + runtime.id
  + runtime.lastError
  + signedInDevices.onDeviceInfoChange
  + signedInDevices.get
  + storage.onChanged
  + storage.StorageArea.clear
  + storage.StorageArea.get
  + storage.StorageArea.remove
  + storage.StorageArea.set
  + storage.local
  + tabs.onAttached
  + tabs.onCreated
  + tabs.onDetached
  + tabs.onMoved
  + tabs.onRemoved
  + tabs.onSelectionChanged
  + tabs.onUpdated
  + tabs.onZoomChange
  + tabs.captureVisibleTab
  + tabs.connect
  + tabs.create
  + tabs.detectLanguage
  + tabs.duplicate
  + tabs.executeScript
  + tabs.get
  + tabs.getAllInWindow
  + tabs.getCurrent
  + tabs.getZoom
  + tabs.getZoomSettings
  + tabs.insertCSS
  + tabs.move
  + tabs.query
  + tabs.remove
  + tabs.sendMessage
  + tabs.sendRequest
  + tabs.setZoom
  + tabs.setZoomSettings
  + tabs.update
  + topSites.get
  + tts.getVoices
  + tts.isSpeaking
  + tts.speak
  + tts.stop
  + ttsEngine.onSpeak
  + ttsEngine.onStop
  + webNavigation.onBeforeNavigate
  + webNavigation.onCommitted
  + webNavigation.onCompleted
  + webNavigation.onCreatedNavigationTarget
  + webNavigation.onDOMContentLoaded
  + webNavigation.onErrorOccurred
  + webNavigation.onHistoryStateUpdated
  + webNavigation.onReferenceFragmentUpdated
  + webRequest.onBeforeRequest
  + windows.onCreated
  + windows.onFocusChanged
  + windows.onRemoved
  + windows.create
  + windows.get
  + windows.getAll
  + windows.getCurrent
  + windows.getLastFocused
  + windows.remove
  + windows.update

## SAMPLES


  + My Bookmarks
  + Page Redder
  + Print this page
  + A browser action which changes its icon when clicked
  + A browser action with a popup that changes the page color
  + BrowsingData API: Basics
  + Sample Extension Commands extension
  + Content settings
  + Context Menus Sample
  + Context Menus Sample (with Event Page)
  + Cookie API Test Extension
  + Live HTTP headers
  + JavaScript pause/resume
  + Desktop Capture Example
  + My Devices
  + Broken Links
  + Chrome Preprocessor Example
  + FirePHP for Chrome
  + Chrome Query
  + Document Scanning API Sample (not available)
  + Download Filename Controller
  + Download Selected Links
  + Download Manager Button
  + Download and Open Button
  + Downloads Overwrite Existing Files
  + Event Page Example
  + `extension.isAllowedFileSchemeAccess` and `extension.isAllowedIncognitoAccess` Example
  + Fake Archive Handler App
  + File System Provider API Extension Example
  + Advanced Font Settings
  + Typed URL History
  + CLD
  + AcceptLanguage
  + Minimal Localized Hosted App
  + Idle - Simple Example
  + Test IME
  + Message Timer
  + Native Messaging Example
  + Notification Demo
  + Omnibox Example
  + Blank new tab page
  + iGoogle new tab page
  + Page action by content
  + Page action by URL
  + Animated Page Action
  + Top Chrome Extension Questions
  + Keep Awake
  + Block/allow third-party cookies API example extension
  + Block/allow referrer API example extension
  + Process Monitor
  + Show Tabs in Process
  + Stylizr
  + Tab Inspector
  + Keyboard Pin
  + Test Screenshot Extension
  + Tabs Zoom API Demo
  + Top Sites
  + NTP prototyping extension
  + Console TTS Engine
  + WebNavigation Tech Demo
  + Merge Windows
  + Simple Background App
  + Calculator
  + App Launcher
  + Chromium Buildbot Monitor
  + Google Calendar Checker (by Google)
  + CatBlock
  + Catifier
  + Chromium Search
  + Email this page (by Google)
  + Chrome Sounds
  + Google Document List Viewer
  + Google Mail Checker
  + Imageinfo
  + Chromium IRC App
  + Managed Bookmarks
  + Mappy
  + Google Maps
  + News Reader (by Google)
  + News Reader
  + News Reader
  + Sample - OAuth Contacts
  + Per-plugin content settings
  + Proxy Extension API Sample
  + Speak Selection
  + Talking Alarm Clock
  + TTS Debug
  + TTS Demo
  + Sandboxed Frame
  + Tab Shortcuts
  + Event Tracking with Google Analytics
  + Getting started example
