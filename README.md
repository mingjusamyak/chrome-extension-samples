## Google Chome Extension Sampples
pffy's COPY-ONLY git mirror of Google Chrome extension samples

+ [LICENSE](#LICENSE)
  + [SUMMARY](#SUMMARY)
    + [CALLS](#CALLS)
    + [SAMPLES](#SAMPLES)

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

The following list links you to **chrome.* API** calls made in the extension samples (for reference).

  + [alarms.onAlarm](https://developer.chrome.com/extensions/alarms#event-onAlarm)
  + [alarms.create](https://developer.chrome.com/extensions/alarms#method-create)
  + [alarms.get](https://developer.chrome.com/extensions/alarms#method-get)
  + [bookmarks.onChanged](https://developer.chrome.com/extensions/bookmarks#event-onChanged)
  + [bookmarks.onCreated](https://developer.chrome.com/extensions/bookmarks#event-onCreated)
  + [bookmarks.onMoved](https://developer.chrome.com/extensions/bookmarks#event-onMoved)
  + [bookmarks.onRemoved](https://developer.chrome.com/extensions/bookmarks#event-onRemoved)
  + [bookmarks.create](https://developer.chrome.com/extensions/bookmarks#method-create)
  + [bookmarks.getChildren](https://developer.chrome.com/extensions/bookmarks#method-getChildren)
  + [bookmarks.getTree](https://developer.chrome.com/extensions/bookmarks#method-getTree)
  + [bookmarks.move](https://developer.chrome.com/extensions/bookmarks#method-move)
  + [bookmarks.remove](https://developer.chrome.com/extensions/bookmarks#method-remove)
  + [bookmarks.removeTree](https://developer.chrome.com/extensions/bookmarks#method-removeTree)
  + [bookmarks.update](https://developer.chrome.com/extensions/bookmarks#method-update)
  + [browserAction.onClicked](https://developer.chrome.com/extensions/browserAction#event-onClicked)
  + [browserAction.setBadgeBackgroundColor](https://developer.chrome.com/extensions/browserAction#method-setBadgeBackgroundColor)
  + [browserAction.setBadgeText](https://developer.chrome.com/extensions/browserAction#method-setBadgeText)
  + [browserAction.setIcon](https://developer.chrome.com/extensions/browserAction#method-setIcon)
  + [browserAction.setTitle](https://developer.chrome.com/extensions/browserAction#method-setTitle)
  + [browsingData.remove](https://developer.chrome.com/extensions/browsingData#method-remove)
  + [commands.onCommand](https://developer.chrome.com/extensions/commands#event-onCommand)
  + [contentSettings.ContentSetting.clear](https://developer.chrome.com/extensions/contentSettings#method-ContentSetting-clear)
  + [contentSettings.ContentSetting.get](https://developer.chrome.com/extensions/contentSettings#method-ContentSetting-get)
  + [contentSettings.ContentSetting.getResourceIdentifiers](https://developer.chrome.com/extensions/contentSettings#method-ContentSetting-getResourceIdentifiers)
  + [contentSettings.ContentSetting.set](https://developer.chrome.com/extensions/contentSettings#method-ContentSetting-set)
  + [contentSettings.plugins](https://developer.chrome.com/extensions/contentSettings#property-plugins)
  + [contextMenus.onClicked](https://developer.chrome.com/extensions/contextMenus#event-onClicked)
  + [contextMenus.create](https://developer.chrome.com/extensions/contextMenus#method-create)
  + [cookies.onChanged](https://developer.chrome.com/extensions/cookies#event-onChanged)
  + [cookies.getAll](https://developer.chrome.com/extensions/cookies#method-getAll)
  + [cookies.remove](https://developer.chrome.com/extensions/cookies#method-remove)
  + [debugger.onDetach](https://developer.chrome.com/extensions/debugger#event-onDetach)
  + [debugger.onEvent](https://developer.chrome.com/extensions/debugger#event-onEvent)
  + [debugger.attach](https://developer.chrome.com/extensions/debugger#method-attach)
  + [debugger.detach](https://developer.chrome.com/extensions/debugger#method-detach)
  + [debugger.sendCommand](https://developer.chrome.com/extensions/debugger#method-sendCommand)
  + [declarativeContent.PageStateMatcher](https://developer.chrome.com/extensions/declarativeContent#type-PageStateMatcher)
  + [declarativeContent.ShowPageAction](https://developer.chrome.com/extensions/declarativeContent#type-ShowPageAction)
  + [declarativeWebRequest.IgnoreRules](https://developer.chrome.com/extensions/declarativeWebRequest#type-IgnoreRules)
  + [declarativeWebRequest.RedirectRequest](https://developer.chrome.com/extensions/declarativeWebRequest#type-RedirectRequest)
  + [declarativeWebRequest.RequestMatcher](https://developer.chrome.com/extensions/declarativeWebRequest#type-RequestMatcher)
  + [desktopCapture.cancelChooseDesktopMedia](https://developer.chrome.com/extensions/desktopCapture#method-cancelChooseDesktopMedia)
  + [desktopCapture.chooseDesktopMedia](https://developer.chrome.com/extensions/desktopCapture#method-chooseDesktopMedia)
  + [devtools.inspectedWindow.eval](https://developer.chrome.com/extensions/devtools.inspectedWindow#method-eval)
  + [devtools.inspectedWindow.reload](https://developer.chrome.com/extensions/devtools.inspectedWindow#method-reload)
  + [devtools.network.onRequestFinished](https://developer.chrome.com/extensions/devtools.network#event-onRequestFinished)
  + [devtools.network.getHAR](https://developer.chrome.com/extensions/devtools.network#method-getHAR)
  + [devtools.panels.ElementsPanel.onSelectionChanged](https://developer.chrome.com/extensions/devtools.panels#event-ElementsPanel-onSelectionChanged)
  + [devtools.panels.create](https://developer.chrome.com/extensions/devtools.panels#method-create)
  + [devtools.panels.ElementsPanel.createSidebarPane](https://developer.chrome.com/extensions/devtools.panels#method-ElementsPanel-createSidebarPane)
  + [documentScan.scan](https://developer.chrome.com/extensions/documentScan#method-scan)
  + [downloads.onChanged](https://developer.chrome.com/extensions/downloads#event-onChanged)
  + [downloads.onCreated](https://developer.chrome.com/extensions/downloads#event-onCreated)
  + [downloads.onDeterminingFilename](https://developer.chrome.com/extensions/downloads#event-onDeterminingFilename)
  + [downloads.onErased](https://developer.chrome.com/extensions/downloads#event-onErased)
  + [downloads.acceptDanger](https://developer.chrome.com/extensions/downloads#method-acceptDanger)
  + [downloads.cancel](https://developer.chrome.com/extensions/downloads#method-cancel)
  + [downloads.download](https://developer.chrome.com/extensions/downloads#method-download)
  + [downloads.drag](https://developer.chrome.com/extensions/downloads#method-drag)
  + [downloads.erase](https://developer.chrome.com/extensions/downloads#method-erase)
  + [downloads.getFileIcon](https://developer.chrome.com/extensions/downloads#method-getFileIcon)
  + [downloads.open](https://developer.chrome.com/extensions/downloads#method-open)
  + [downloads.pause](https://developer.chrome.com/extensions/downloads#method-pause)
  + [downloads.removeFile](https://developer.chrome.com/extensions/downloads#method-removeFile)
  + [downloads.resume](https://developer.chrome.com/extensions/downloads#method-resume)
  + [downloads.search](https://developer.chrome.com/extensions/downloads#method-search)
  + [downloads.setShelfEnabled](https://developer.chrome.com/extensions/downloads#method-setShelfEnabled)
  + [downloads.show](https://developer.chrome.com/extensions/downloads#method-show)
  + [downloads.showDefaultFolder](https://developer.chrome.com/extensions/downloads#method-showDefaultFolder)
  + [experimental.devtools.audits.addCategory](https://developer.chrome.com/extensions/experimental.devtools.audits#method-addCategory)
  + [extension.onRequest](https://developer.chrome.com/extensions/extension#event-onRequest)
  + [extension.getBackgroundPage](https://developer.chrome.com/extensions/extension#method-getBackgroundPage)
  + [extension.getURL](https://developer.chrome.com/extensions/extension#method-getURL)
  + [extension.getViews](https://developer.chrome.com/extensions/extension#method-getViews)
  + [extension.isAllowedFileSchemeAccess](https://developer.chrome.com/extensions/extension#method-isAllowedFileSchemeAccess)
  + [extension.isAllowedIncognitoAccess](https://developer.chrome.com/extensions/extension#method-isAllowedIncognitoAccess)
  + [extension.sendRequest](https://developer.chrome.com/extensions/extension#method-sendRequest)
  + [extension.lastError](https://developer.chrome.com/extensions/extension#property-lastError)
  + [fileSystemProvider.onCloseFileRequested](https://developer.chrome.com/extensions/fileSystemProvider#event-onCloseFileRequested)
  + [fileSystemProvider.onGetMetadataRequested](https://developer.chrome.com/extensions/fileSystemProvider#event-onGetMetadataRequested)
  + [fileSystemProvider.onOpenFileRequested](https://developer.chrome.com/extensions/fileSystemProvider#event-onOpenFileRequested)
  + [fileSystemProvider.onReadDirectoryRequested](https://developer.chrome.com/extensions/fileSystemProvider#event-onReadDirectoryRequested)
  + [fileSystemProvider.onReadFileRequested](https://developer.chrome.com/extensions/fileSystemProvider#event-onReadFileRequested)
  + [fileSystemProvider.onUnmountRequested](https://developer.chrome.com/extensions/fileSystemProvider#event-onUnmountRequested)
  + [fileSystemProvider.mount](https://developer.chrome.com/extensions/fileSystemProvider#method-mount)
  + [fileSystemProvider.unmount](https://developer.chrome.com/extensions/fileSystemProvider#method-unmount)
  + [fontSettings.onDefaultFixedFontSizeChanged](https://developer.chrome.com/extensions/fontSettings#event-onDefaultFixedFontSizeChanged)
  + [fontSettings.onDefaultFontSizeChanged](https://developer.chrome.com/extensions/fontSettings#event-onDefaultFontSizeChanged)
  + [fontSettings.onFontChanged](https://developer.chrome.com/extensions/fontSettings#event-onFontChanged)
  + [fontSettings.onMinimumFontSizeChanged](https://developer.chrome.com/extensions/fontSettings#event-onMinimumFontSizeChanged)
  + [fontSettings.clearDefaultFixedFontSize](https://developer.chrome.com/extensions/fontSettings#method-clearDefaultFixedFontSize)
  + [fontSettings.clearDefaultFontSize](https://developer.chrome.com/extensions/fontSettings#method-clearDefaultFontSize)
  + [fontSettings.clearFont](https://developer.chrome.com/extensions/fontSettings#method-clearFont)
  + [fontSettings.clearMinimumFontSize](https://developer.chrome.com/extensions/fontSettings#method-clearMinimumFontSize)
  + [fontSettings.getDefaultFixedFontSize](https://developer.chrome.com/extensions/fontSettings#method-getDefaultFixedFontSize)
  + [fontSettings.getDefaultFontSize](https://developer.chrome.com/extensions/fontSettings#method-getDefaultFontSize)
  + [fontSettings.getFont](https://developer.chrome.com/extensions/fontSettings#method-getFont)
  + [fontSettings.getFontList](https://developer.chrome.com/extensions/fontSettings#method-getFontList)
  + [fontSettings.getMinimumFontSize](https://developer.chrome.com/extensions/fontSettings#method-getMinimumFontSize)
  + [fontSettings.setDefaultFixedFontSize](https://developer.chrome.com/extensions/fontSettings#method-setDefaultFixedFontSize)
  + [fontSettings.setDefaultFontSize](https://developer.chrome.com/extensions/fontSettings#method-setDefaultFontSize)
  + [fontSettings.setFont](https://developer.chrome.com/extensions/fontSettings#method-setFont)
  + [fontSettings.setMinimumFontSize](https://developer.chrome.com/extensions/fontSettings#method-setMinimumFontSize)
  + [history.getVisits](https://developer.chrome.com/extensions/history#method-getVisits)
  + [history.search](https://developer.chrome.com/extensions/history#method-search)
  + [i18n.getAcceptLanguages](https://developer.chrome.com/extensions/i18n#method-getAcceptLanguages)
  + [i18n.getMessage](https://developer.chrome.com/extensions/i18n#method-getMessage)
  + [idle.onStateChanged](https://developer.chrome.com/extensions/idle#event-onStateChanged)
  + [idle.queryState](https://developer.chrome.com/extensions/idle#method-queryState)
  + [input.ime.onActivate](https://developer.chrome.com/extensions/input.ime#event-onActivate)
  + [input.ime.onBlur](https://developer.chrome.com/extensions/input.ime#event-onBlur)
  + [input.ime.onDeactivated](https://developer.chrome.com/extensions/input.ime#event-onDeactivated)
  + [input.ime.onFocus](https://developer.chrome.com/extensions/input.ime#event-onFocus)
  + [input.ime.onKeyEvent](https://developer.chrome.com/extensions/input.ime#event-onKeyEvent)
  + [input.ime.commitText](https://developer.chrome.com/extensions/input.ime#method-commitText)
  + [management.getAll](https://developer.chrome.com/extensions/management#method-getAll)
  + [management.launchApp](https://developer.chrome.com/extensions/management#method-launchApp)
  + [management.uninstallSelf](https://developer.chrome.com/extensions/management#method-uninstallSelf)
  + [notifications.onButtonClicked](https://developer.chrome.com/extensions/notifications#event-onButtonClicked)
  + [notifications.onClicked](https://developer.chrome.com/extensions/notifications#event-onClicked)
  + [notifications.clear](https://developer.chrome.com/extensions/notifications#method-clear)
  + [notifications.create](https://developer.chrome.com/extensions/notifications#method-create)
  + [omnibox.onInputCancelled](https://developer.chrome.com/extensions/omnibox#event-onInputCancelled)
  + [omnibox.onInputChanged](https://developer.chrome.com/extensions/omnibox#event-onInputChanged)
  + [omnibox.onInputEntered](https://developer.chrome.com/extensions/omnibox#event-onInputEntered)
  + [omnibox.onInputStarted](https://developer.chrome.com/extensions/omnibox#event-onInputStarted)
  + [omnibox.setDefaultSuggestion](https://developer.chrome.com/extensions/omnibox#method-setDefaultSuggestion)
  + [pageAction.onClicked](https://developer.chrome.com/extensions/pageAction#event-onClicked)
  + [pageAction.hide](https://developer.chrome.com/extensions/pageAction#method-hide)
  + [pageAction.setIcon](https://developer.chrome.com/extensions/pageAction#method-setIcon)
  + [pageAction.setTitle](https://developer.chrome.com/extensions/pageAction#method-setTitle)
  + [pageAction.show](https://developer.chrome.com/extensions/pageAction#method-show)
  + [permissions.onAdded](https://developer.chrome.com/extensions/permissions#event-onAdded)
  + [permissions.onRemoved](https://developer.chrome.com/extensions/permissions#event-onRemoved)
  + [permissions.contains](https://developer.chrome.com/extensions/permissions#method-contains)
  + [permissions.remove](https://developer.chrome.com/extensions/permissions#method-remove)
  + [permissions.request](https://developer.chrome.com/extensions/permissions#method-request)
  + [power.releaseKeepAwake](https://developer.chrome.com/extensions/power#method-releaseKeepAwake)
  + [power.requestKeepAwake](https://developer.chrome.com/extensions/power#method-requestKeepAwake)
  + [processes.onUpdatedWithMemory](https://developer.chrome.com/extensions/processes#event-onUpdatedWithMemory)
  + [processes.getProcessIdForTab](https://developer.chrome.com/extensions/processes#method-getProcessIdForTab)
  + [processes.terminate](https://developer.chrome.com/extensions/processes#method-terminate)
  + [proxy.onProxyError](https://developer.chrome.com/extensions/proxy#event-onProxyError)
  + [runtime.onConnect](https://developer.chrome.com/extensions/runtime#event-onConnect)
  + [runtime.onInstalled](https://developer.chrome.com/extensions/runtime#event-onInstalled)
  + [runtime.onMessage](https://developer.chrome.com/extensions/runtime#event-onMessage)
  + [runtime.onStartup](https://developer.chrome.com/extensions/runtime#event-onStartup)
  + [runtime.onSuspend](https://developer.chrome.com/extensions/runtime#event-onSuspend)
  + [runtime.connect](https://developer.chrome.com/extensions/runtime#method-connect)
  + [runtime.connectNative](https://developer.chrome.com/extensions/runtime#method-connectNative)
  + [runtime.getURL](https://developer.chrome.com/extensions/runtime#method-getURL)
  + [runtime.sendMessage](https://developer.chrome.com/extensions/runtime#method-sendMessage)
  + [runtime.id](https://developer.chrome.com/extensions/runtime#property-id)
  + [runtime.lastError](https://developer.chrome.com/extensions/runtime#property-lastError)
  + [signedInDevices.onDeviceInfoChange](https://developer.chrome.com/extensions/signedInDevices#event-onDeviceInfoChange)
  + [signedInDevices.get](https://developer.chrome.com/extensions/signedInDevices#method-get)
  + [storage.onChanged](https://developer.chrome.com/extensions/storage#event-onChanged)
  + [storage.StorageArea.clear](https://developer.chrome.com/extensions/storage#method-StorageArea-clear)
  + [storage.StorageArea.get](https://developer.chrome.com/extensions/storage#method-StorageArea-get)
  + [storage.StorageArea.remove](https://developer.chrome.com/extensions/storage#method-StorageArea-remove)
  + [storage.StorageArea.set](https://developer.chrome.com/extensions/storage#method-StorageArea-set)
  + [storage.local](https://developer.chrome.com/extensions/storage#property-local)
  + [tabs.onAttached](https://developer.chrome.com/extensions/tabs#event-onAttached)
  + [tabs.onCreated](https://developer.chrome.com/extensions/tabs#event-onCreated)
  + [tabs.onDetached](https://developer.chrome.com/extensions/tabs#event-onDetached)
  + [tabs.onMoved](https://developer.chrome.com/extensions/tabs#event-onMoved)
  + [tabs.onRemoved](https://developer.chrome.com/extensions/tabs#event-onRemoved)
  + [tabs.onSelectionChanged](https://developer.chrome.com/extensions/tabs#event-onSelectionChanged)
  + [tabs.onUpdated](https://developer.chrome.com/extensions/tabs#event-onUpdated)
  + [tabs.onZoomChange](https://developer.chrome.com/extensions/tabs#event-onZoomChange)
  + [tabs.captureVisibleTab](https://developer.chrome.com/extensions/tabs#method-captureVisibleTab)
  + [tabs.connect](https://developer.chrome.com/extensions/tabs#method-connect)
  + [tabs.create](https://developer.chrome.com/extensions/tabs#method-create)
  + [tabs.detectLanguage](https://developer.chrome.com/extensions/tabs#method-detectLanguage)
  + [tabs.duplicate](https://developer.chrome.com/extensions/tabs#method-duplicate)
  + [tabs.executeScript](https://developer.chrome.com/extensions/tabs#method-executeScript)
  + [tabs.get](https://developer.chrome.com/extensions/tabs#method-get)
  + [tabs.getAllInWindow](https://developer.chrome.com/extensions/tabs#method-getAllInWindow)
  + [tabs.getCurrent](https://developer.chrome.com/extensions/tabs#method-getCurrent)
  + [tabs.getZoom](https://developer.chrome.com/extensions/tabs#method-getZoom)
  + [tabs.getZoomSettings](https://developer.chrome.com/extensions/tabs#method-getZoomSettings)
  + [tabs.insertCSS](https://developer.chrome.com/extensions/tabs#method-insertCSS)
  + [tabs.move](https://developer.chrome.com/extensions/tabs#method-move)
  + [tabs.query](https://developer.chrome.com/extensions/tabs#method-query)
  + [tabs.remove](https://developer.chrome.com/extensions/tabs#method-remove)
  + [tabs.sendMessage](https://developer.chrome.com/extensions/tabs#method-sendMessage)
  + [tabs.sendRequest](https://developer.chrome.com/extensions/tabs#method-sendRequest)
  + [tabs.setZoom](https://developer.chrome.com/extensions/tabs#method-setZoom)
  + [tabs.setZoomSettings](https://developer.chrome.com/extensions/tabs#method-setZoomSettings)
  + [tabs.update](https://developer.chrome.com/extensions/tabs#method-update)
  + [topSites.get](https://developer.chrome.com/extensions/topSites#method-get)
  + [tts.getVoices](https://developer.chrome.com/extensions/tts#method-getVoices)
  + [tts.isSpeaking](https://developer.chrome.com/extensions/tts#method-isSpeaking)
  + [tts.speak](https://developer.chrome.com/extensions/tts#method-speak)
  + [tts.stop](https://developer.chrome.com/extensions/tts#method-stop)
  + [ttsEngine.onSpeak](https://developer.chrome.com/extensions/ttsEngine#event-onSpeak)
  + [ttsEngine.onStop](https://developer.chrome.com/extensions/ttsEngine#event-onStop)
  + [webNavigation.onBeforeNavigate](https://developer.chrome.com/extensions/webNavigation#event-onBeforeNavigate)
  + [webNavigation.onCommitted](https://developer.chrome.com/extensions/webNavigation#event-onCommitted)
  + [webNavigation.onCompleted](https://developer.chrome.com/extensions/webNavigation#event-onCompleted)
  + [webNavigation.onCreatedNavigationTarget](https://developer.chrome.com/extensions/webNavigation#event-onCreatedNavigationTarget)
  + [webNavigation.onDOMContentLoaded](https://developer.chrome.com/extensions/webNavigation#event-onDOMContentLoaded)
  + [webNavigation.onErrorOccurred](https://developer.chrome.com/extensions/webNavigation#event-onErrorOccurred)
  + [webNavigation.onHistoryStateUpdated](https://developer.chrome.com/extensions/webNavigation#event-onHistoryStateUpdated)
  + [webNavigation.onReferenceFragmentUpdated](https://developer.chrome.com/extensions/webNavigation#event-onReferenceFragmentUpdated)
  + [webRequest.onBeforeRequest](https://developer.chrome.com/extensions/webRequest#event-onBeforeRequest)
  + [windows.onCreated](https://developer.chrome.com/extensions/windows#event-onCreated)
  + [windows.onFocusChanged](https://developer.chrome.com/extensions/windows#event-onFocusChanged)
  + [windows.onRemoved](https://developer.chrome.com/extensions/windows#event-onRemoved)
  + [windows.create](https://developer.chrome.com/extensions/windows#method-create)
  + [windows.get](https://developer.chrome.com/extensions/windows#method-get)
  + [windows.getAll](https://developer.chrome.com/extensions/windows#method-getAll)
  + [windows.getCurrent](https://developer.chrome.com/extensions/windows#method-getCurrent)
  + [windows.getLastFocused](https://developer.chrome.com/extensions/windows#method-getLastFocused)
  + [windows.remove](https://developer.chrome.com/extensions/windows#method-remove)
  + [windows.update](https://developer.chrome.com/extensions/windows#method-update)

## SAMPLES

  The following list links you directly to Google Chrome sample extension information and zip files (for reference).

  + [My Bookmarks](https://developer.chrome.com/extensions/samples#my-bookmarks)  [ [zip](https://developer.chrome.com/extensions/examples/api/bookmarks/basic.zip) ]
  + [Page Redder](https://developer.chrome.com/extensions/samples#page-redder)  [ [zip](https://developer.chrome.com/extensions/examples/api/browserAction/make_page_red.zip) ]
  + [Print this page](https://developer.chrome.com/extensions/samples#print-this-page)  [ [zip](https://developer.chrome.com/extensions/examples/api/browserAction/print.zip) ]
  + [A browser action which changes its icon when clicked](https://developer.chrome.com/extensions/samples#a-browser-action-which-changes-its-icon-when-clicked)  [ [zip](https://developer.chrome.com/extensions/examples/api/browserAction/set_icon_path.zip) ]
  + [A browser action with a popup that changes the page color](https://developer.chrome.com/extensions/samples#a-browser-action-with-a-popup-that-changes-the-page-color)  [ [zip](https://developer.chrome.com/extensions/examples/api/browserAction/set_page_color.zip) ]
  + [BrowsingData API: Basics](https://developer.chrome.com/extensions/samples#browsingdata-api:-basics)  [ [zip](https://developer.chrome.com/extensions/examples/api/browsingData/basic.zip) ]
  + [Sample Extension Commands extension](https://developer.chrome.com/extensions/samples#sample-extension-commands-extension)  [ [zip](https://developer.chrome.com/extensions/examples/api/commands.zip) ]
  + [Content settings](https://developer.chrome.com/extensions/samples#content-settings)  [ [zip](https://developer.chrome.com/extensions/examples/api/contentSettings.zip) ]
  + [Context Menus Sample](https://developer.chrome.com/extensions/samples#context-menus-sample)  [ [zip](https://developer.chrome.com/extensions/examples/api/contextMenus/basic.zip) ]
  + [Context Menus Sample (with Event Page)](https://developer.chrome.com/extensions/samples#context-menus-sample-(with-event-page))  [ [zip](https://developer.chrome.com/extensions/examples/api/contextMenus/event_page.zip) ]
  + [Cookie API Test Extension](https://developer.chrome.com/extensions/samples#cookie-api-test-extension)  [ [zip](https://developer.chrome.com/extensions/examples/api/cookies.zip) ]
  + [Live HTTP headers](https://developer.chrome.com/extensions/samples#live-http-headers)  [ [zip](https://developer.chrome.com/extensions/examples/api/debugger/live-headers.zip) ]
  + [JavaScript pause/resume](https://developer.chrome.com/extensions/samples#javascript-pause/resume)  [ [zip](https://developer.chrome.com/extensions/examples/api/debugger/pause-resume.zip) ]
  + [Desktop Capture Example](https://developer.chrome.com/extensions/samples#desktop-capture-example)  [ [zip](https://developer.chrome.com/extensions/examples/api/desktopCapture.zip) ]
  + [My Devices](https://developer.chrome.com/extensions/samples#my-devices)  [ [zip](https://developer.chrome.com/extensions/examples/api/deviceInfo/basic.zip) ]
  + [Broken Links](https://developer.chrome.com/extensions/samples#broken-links)  [ [zip](https://developer.chrome.com/extensions/examples/api/devtools/audits/broken-links.zip) ]
  + [Chrome Preprocessor Example](https://developer.chrome.com/extensions/samples#chrome-preprocessor-example)  [ [zip](https://developer.chrome.com/extensions/examples/api/devtools/inspectedWindow/chrome-preprocessor.zip) ]
  + [FirePHP for Chrome](https://developer.chrome.com/extensions/samples#firephp-for-chrome)  [ [zip](https://developer.chrome.com/extensions/examples/api/devtools/network/chrome-firephp.zip) ]
  + [Chrome Query](https://developer.chrome.com/extensions/samples#chrome-query)  [ [zip](https://developer.chrome.com/extensions/examples/api/devtools/panels/chrome-query.zip) ]
  + [Document Scanning API Sample](https://developer.chrome.com/extensions/samples#document-scanning-api-sample)  [ [zip](https://developer.chrome.com/extensions/examples/api/document_scan.zip) ]
  + [Download Filename Controller](https://developer.chrome.com/extensions/samples#download-filename-controller)  [ [zip](https://developer.chrome.com/extensions/examples/api/downloads/download_filename_controller.zip) ]
  + [Download Selected Links](https://developer.chrome.com/extensions/samples#download-selected-links)  [ [zip](https://developer.chrome.com/extensions/examples/api/downloads/download_links.zip) ]
  + [Download Manager Button](https://developer.chrome.com/extensions/samples#download-manager-button)  [ [zip](https://developer.chrome.com/extensions/examples/api/downloads/download_manager.zip) ]
  + [Download and Open Button](https://developer.chrome.com/extensions/samples#download-and-open-button)  [ [zip](https://developer.chrome.com/extensions/examples/api/downloads/download_open.zip) ]
  + [Downloads Overwrite Existing Files](https://developer.chrome.com/extensions/samples#downloads-overwrite-existing-files)  [ [zip](https://developer.chrome.com/extensions/examples/api/downloads/downloads_overwrite.zip) ]
  + [Event Page Example](https://developer.chrome.com/extensions/samples#event-page-example)  [ [zip](https://developer.chrome.com/extensions/examples/api/eventPage/basic.zip) ]
  + [`extension.isAllowedFileSchemeAccess` and `extension.isAllowedIncognitoAccess` Example](https://developer.chrome.com/extensions/samples#`extension.isallowedfileschemeaccess`-and-`extension.isallowedincognitoaccess`-example)  [ [zip](https://developer.chrome.com/extensions/examples/api/extension/isAllowedAccess.zip) ]
  + [Fake Archive Handler App](https://developer.chrome.com/extensions/samples#fake-archive-handler-app)  [ [zip](https://developer.chrome.com/extensions/examples/api/fileSystemProvider/archive.zip) ]
  + [File System Provider API Extension Example](https://developer.chrome.com/extensions/samples#file-system-provider-api-extension-example)  [ [zip](https://developer.chrome.com/extensions/examples/api/fileSystemProvider/basic.zip) ]
  + [Advanced Font Settings](https://developer.chrome.com/extensions/samples#advanced-font-settings)  [ [zip](https://developer.chrome.com/extensions/examples/api/fontSettings.zip) ]
  + [Typed URL History](https://developer.chrome.com/extensions/samples#typed-url-history)  [ [zip](https://developer.chrome.com/extensions/examples/api/history/showHistory.zip) ]
  + [CLD](https://developer.chrome.com/extensions/samples#cld)  [ [zip](https://developer.chrome.com/extensions/examples/api/i18n/cld.zip) ]
  + [AcceptLanguage](https://developer.chrome.com/extensions/samples#acceptlanguage)  [ [zip](https://developer.chrome.com/extensions/examples/api/i18n/getMessage.zip) ]
  + [Minimal Localized Hosted App](https://developer.chrome.com/extensions/samples#minimal-localized-hosted-app)  [ [zip](https://developer.chrome.com/extensions/examples/api/i18n/localizedHostedApp.zip) ]
  + [Idle - Simple Example](https://developer.chrome.com/extensions/samples#idle---simple-example)  [ [zip](https://developer.chrome.com/extensions/examples/api/idle/idle_simple.zip) ]
  + [Test IME](https://developer.chrome.com/extensions/samples#test-ime)  [ [zip](https://developer.chrome.com/extensions/examples/api/input.ime/basic.zip) ]
  + [Message Timer](https://developer.chrome.com/extensions/samples#message-timer)  [ [zip](https://developer.chrome.com/extensions/examples/api/messaging/timer.zip) ]
  + [Native Messaging Example](https://developer.chrome.com/extensions/samples#native-messaging-example)  [ [zip](https://developer.chrome.com/extensions/examples/api/nativeMessaging/app.zip) ]
  + [Notification Demo](https://developer.chrome.com/extensions/samples#notification-demo)  [ [zip](https://developer.chrome.com/extensions/examples/api/notifications.zip) ]
  + [Omnibox Example](https://developer.chrome.com/extensions/samples#omnibox-example)  [ [zip](https://developer.chrome.com/extensions/examples/api/omnibox/simple-example.zip) ]
  + [Blank new tab page](https://developer.chrome.com/extensions/samples#blank-new-tab-page)  [ [zip](https://developer.chrome.com/extensions/examples/api/override/blank_ntp.zip) ]
  + [iGoogle new tab page](https://developer.chrome.com/extensions/samples#igoogle-new-tab-page)  [ [zip](https://developer.chrome.com/extensions/examples/api/override/override_igoogle.zip) ]
  + [Page action by content](https://developer.chrome.com/extensions/samples#page-action-by-content)  [ [zip](https://developer.chrome.com/extensions/examples/api/pageAction/pageaction_by_content.zip) ]
  + [Page action by URL](https://developer.chrome.com/extensions/samples#page-action-by-url)  [ [zip](https://developer.chrome.com/extensions/examples/api/pageAction/pageaction_by_url.zip) ]
  + [Animated Page Action](https://developer.chrome.com/extensions/samples#animated-page-action)  [ [zip](https://developer.chrome.com/extensions/examples/api/pageAction/set_icon.zip) ]
  + [Top Chrome Extension Questions](https://developer.chrome.com/extensions/samples#top-chrome-extension-questions)  [ [zip](https://developer.chrome.com/extensions/examples/api/permissions/extension-questions.zip) ]
  + [Keep Awake](https://developer.chrome.com/extensions/samples#keep-awake)  [ [zip](https://developer.chrome.com/extensions/examples/api/power.zip) ]
  + [Block/allow third-party cookies API example extension](https://developer.chrome.com/extensions/samples#block/allow-third-party-cookies-api-example-extension)  [ [zip](https://developer.chrome.com/extensions/examples/api/preferences/allowThirdPartyCookies.zip) ]
  + [Block/allow referrer API example extension](https://developer.chrome.com/extensions/samples#block/allow-referrer-api-example-extension)  [ [zip](https://developer.chrome.com/extensions/examples/api/preferences/enableReferrer.zip) ]
  + [Process Monitor](https://developer.chrome.com/extensions/samples#process-monitor)  [ [zip](https://developer.chrome.com/extensions/examples/api/processes/process_monitor.zip) ]
  + [Show Tabs in Process](https://developer.chrome.com/extensions/samples#show-tabs-in-process)  [ [zip](https://developer.chrome.com/extensions/examples/api/processes/show_tabs.zip) ]
  + [Stylizr](https://developer.chrome.com/extensions/samples#stylizr)  [ [zip](https://developer.chrome.com/extensions/examples/api/storage/stylizr.zip) ]
  + [Tab Inspector](https://developer.chrome.com/extensions/samples#tab-inspector)  [ [zip](https://developer.chrome.com/extensions/examples/api/tabs/inspector.zip) ]
  + [Keyboard Pin](https://developer.chrome.com/extensions/samples#keyboard-pin)  [ [zip](https://developer.chrome.com/extensions/examples/api/tabs/pin.zip) ]
  + [Test Screenshot Extension](https://developer.chrome.com/extensions/samples#test-screenshot-extension)  [ [zip](https://developer.chrome.com/extensions/examples/api/tabs/screenshot.zip) ]
  + [Tabs Zoom API Demo](https://developer.chrome.com/extensions/samples#tabs-zoom-api-demo)  [ [zip](https://developer.chrome.com/extensions/examples/api/tabs/zoom.zip) ]
  + [Top Sites](https://developer.chrome.com/extensions/samples#top-sites)  [ [zip](https://developer.chrome.com/extensions/examples/api/topsites/basic.zip) ]
  + [NTP prototyping extension](https://developer.chrome.com/extensions/samples#ntp-prototyping-extension)  [ [zip](https://developer.chrome.com/extensions/examples/api/topsites/magic8ball.zip) ]
  + [Console TTS Engine](https://developer.chrome.com/extensions/samples#console-tts-engine)  [ [zip](https://developer.chrome.com/extensions/examples/api/ttsEngine/console_tts_engine.zip) ]
  + [WebNavigation Tech Demo](https://developer.chrome.com/extensions/samples#webnavigation-tech-demo)  [ [zip](https://developer.chrome.com/extensions/examples/api/webNavigation/basic.zip) ]
  + [Merge Windows](https://developer.chrome.com/extensions/samples#merge-windows)  [ [zip](https://developer.chrome.com/extensions/examples/api/windows/merge_windows.zip) ]
  + [Simple Background App](https://developer.chrome.com/extensions/samples#simple-background-app)  [ [zip](https://developer.chrome.com/extensions/examples/apps/background-simple.zip) ]
  + [Calculator](https://developer.chrome.com/extensions/samples#calculator)  [ [zip](https://developer.chrome.com/extensions/examples/apps/calculator/app.zip) ]
  + [App Launcher](https://developer.chrome.com/extensions/samples#app-launcher)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/app_launcher.zip) ]
  + [Chromium Buildbot Monitor](https://developer.chrome.com/extensions/samples#chromium-buildbot-monitor)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/buildbot.zip) ]
  + [Google Calendar Checker (by Google)](https://developer.chrome.com/extensions/samples#google-calendar-checker-(by-google))  [ [zip](https://developer.chrome.com/extensions/examples/extensions/calendar.zip) ]
  + [CatBlock](https://developer.chrome.com/extensions/samples#catblock)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/catblock.zip) ]
  + [Catifier](https://developer.chrome.com/extensions/samples#catifier)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/catifier.zip) ]
  + [Chromium Search](https://developer.chrome.com/extensions/samples#chromium-search)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/chrome_search.zip) ]
  + [Email this page (by Google)](https://developer.chrome.com/extensions/samples#email-this-page-(by-google))  [ [zip](https://developer.chrome.com/extensions/examples/extensions/email_this_page.zip) ]
  + [Chrome Sounds](https://developer.chrome.com/extensions/samples#chrome-sounds)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/fx.zip) ]
  + [Google Document List Viewer](https://developer.chrome.com/extensions/samples#google-document-list-viewer)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/gdocs.zip) ]
  + [Google Mail Checker](https://developer.chrome.com/extensions/samples#google-mail-checker)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/gmail.zip) ]
  + [Imageinfo](https://developer.chrome.com/extensions/samples#imageinfo)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/imageinfo.zip) ]
  + [Chromium IRC App](https://developer.chrome.com/extensions/samples#chromium-irc-app)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/irc/app.zip) ]
  + [Managed Bookmarks](https://developer.chrome.com/extensions/samples#managed-bookmarks)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/managed_bookmarks.zip) ]
  + [Mappy](https://developer.chrome.com/extensions/samples#mappy)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/mappy.zip) ]
  + [Google Maps](https://developer.chrome.com/extensions/samples#google-maps)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/maps_app.zip) ]
  + [News Reader (by Google)](https://developer.chrome.com/extensions/samples#news-reader-(by-google))  [ [zip](https://developer.chrome.com/extensions/examples/extensions/news.zip) ]
  + [News Reader](https://developer.chrome.com/extensions/samples#news-reader)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/news_a11y.zip) ]
  + [News Reader](https://developer.chrome.com/extensions/samples#news-reader)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/news_i18n.zip) ]
  + [Sample - OAuth Contacts](https://developer.chrome.com/extensions/samples#sample---oauth-contacts)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/oauth_contacts.zip) ]
  + [Per-plugin content settings](https://developer.chrome.com/extensions/samples#per-plugin-content-settings)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/plugin_settings.zip) ]
  + [Proxy Extension API Sample](https://developer.chrome.com/extensions/samples#proxy-extension-api-sample)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/proxy_configuration.zip) ]
  + [Speak Selection](https://developer.chrome.com/extensions/samples#speak-selection)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/speak_selection.zip) ]
  + [Talking Alarm Clock](https://developer.chrome.com/extensions/samples#talking-alarm-clock)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/talking_alarm_clock.zip) ]
  + [TTS Debug](https://developer.chrome.com/extensions/samples#tts-debug)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/ttsdebug.zip) ]
  + [TTS Demo](https://developer.chrome.com/extensions/samples#tts-demo)  [ [zip](https://developer.chrome.com/extensions/examples/extensions/ttsdemo.zip) ]
  + [Sandboxed Frame](https://developer.chrome.com/extensions/samples#sandboxed-frame)  [ [zip](https://developer.chrome.com/extensions/examples/howto/sandbox.zip) ]
  + [Tab Shortcuts](https://developer.chrome.com/extensions/samples#tab-shortcuts)  [ [zip](https://developer.chrome.com/extensions/examples/howto/tab_shortcuts.zip) ]
  + [Event Tracking with Google Analytics](https://developer.chrome.com/extensions/samples#event-tracking-with-google-analytics)  [ [zip](https://developer.chrome.com/extensions/examples/tutorials/analytics.zip) ]
  + [Getting started example](https://developer.chrome.com/extensions/samples#getting-started-example)  [ [zip](https://developer.chrome.com/extensions/examples/tutorials/getstarted.zip) ]
