# Registry Settings

## Disable Print Screen key mapping to Snipping Tool

Set `HKCU\Control Panel\Keyboard\PrintScreenKeyForSnippingEnabled` to `0` (`DWORD`).

## Remove advertiser ID

Delete `HKCU\Software\Microsoft\Windows\CurrentVersion\AdvertisingInfo\Id`.

Also: `HKCU\Software\Microsoft\Windows\CurrentVersion\CPSS\Store\AdvertisingInfo\Value` to `DWORD` of `0`

`HKCU\Software\Microsoft\Windows\CurrentVersion\AdvertisingInfo\Enabled` to `0`

## Don't let websites show locally relevant content through language list

`HKCU\Control Panel\International\User Profile\HttpAcceptLanguageOptOut` to `1`

## Don't track app launches

`HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\Start_TrackProgs` to `0`

## Don't show suggested content in settings

`HKCU\Software\Microsoft\Windows\CurrentVersion\ContentDeliveryManager\SubscribedContent-338386Enabled` to `0`
`HKCU\Software\Microsoft\Windows\CurrentVersion\ContentDeliveryManager\SubscribedContent-353695Enabled`
`HKCU\Software\Microsoft\Windows\CurrentVersion\ContentDeliveryManager\SubscribedContent-353697Enabled`

## No inking personalization

`HKCU\Software\Microsoft\Windows\CurrentVersion\CPSS\Store\InkingAndTypingPersonalization\Value` to `0`
`HKCU\Software\Microsoft\Personalization\Settings\AcceptedPrivacyPolicy` to `0`
`HKCU\Software\Microsoft\InputPersonalization\RestrictImplicitTextCollection` to `1`
`HKCU\Software\Microsoft\InputPersonalization\RestrictImplicitInkCollection` to `1`
`HKCU\Software\Microsoft\InputPersonalization\TrainedDataStore\HarvestContacts` to `0`
`HKCU\Software\Microsoft\Windows\CurrentVersion\CPSS\Store\IME\Bopomofo\Enable New Phrase Learning\Value` to `Type: REG_SZ, Length: 22, Data: 0x00000001`
`HKCU\Software\Microsoft\IME\15.0\IMETC\Enable New Phrase Learning` to `Type: REG_SZ, Length: 22, Data: 0x00000001`
`HKCU\Software\Microsoft\Windows\CurrentVersion\CPSS\Store\IME\Bopomofo\Enable Personal Regulating\Value` to `Type: REG_SZ, Length: 22, Data: 0x00000001`

HKCU\Software\Microsoft\IME\15.0\IMETC\Enable Personal Regulating	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000001
HKCU\Software\Microsoft\Windows\CurrentVersion\CPSS\Store\IME\Bopomofo\Fixed Candidate Order.New Phonetic\Value	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000000
HKCU\Software\Microsoft\IME\15.0\IMETC\Fixed Candidate Order.New Phonetic	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000000
HKCU\Software\Microsoft\Windows\CurrentVersion\CPSS\Store\IME\Bopomofo\Enable User Defined Phrases\Value	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000001
HKCU\Software\Microsoft\IME\15.0\IMETC\Enable User Defined Phrases	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000001
HKCU\Software\Microsoft\IME\15.0\IMETC\Enable Warning Beep Feedback	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000001
HKCU\Software\Microsoft\IME\15.0\IMETC\Left Shift Usage	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000000
HKCU\Software\Microsoft\IME\15.0\IMETC\Right Shift Usage	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000001
HKCU\Software\Microsoft\IME\15.0\IMETC\Default Input Mode	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000000
HKCU\Software\Microsoft\IME\15.0\IMETC\Output Big5 Only	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000000
HKCU\Software\Microsoft\IME\15.0\IMETC\Include Extension A Characters	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000000
HKCU\Software\Microsoft\IME\15.0\IMETC\Include Extension B Characters	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000000
HKCU\Software\Microsoft\IME\15.0\IMETC\Allow CNS Input Sequence	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000000
HKCU\Software\Microsoft\IME\15.0\IMETC\Include HKSCS Characters	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000000
HKCU\Software\Microsoft\IME\15.0\IMETC\Fuzzy Pairs	SUCCESS	Type: REG_BINARY, Length: 8,328, Data: 00 00 00 00 10 02 00 00 05 31 00 00 00 00 00 00
HKCU\Software\Microsoft\IME\15.0\IMETC\Enable Intelligent Auto Input Switch	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000000
HKCU\Software\Microsoft\IME\15.0\IMETC\Enable Switch Character Width Hotkey	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000001
HKCU\Software\Microsoft\IME\15.0\IMETC\Enable Punctuation Auto Finalize	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000000
HKCU\Software\Microsoft\IME\15.0\IMETC\Enable Fuzzy Input	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000000
HKCU\Software\Microsoft\Windows\CurrentVersion\CPSS\Store\IME\Bopomofo\Enable New Phrase Learning\Value	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000001
HKCU\Software\Microsoft\IME\15.0\IMETC\Enable New Phrase Learning	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000001
HKCU\Software\Microsoft\Windows\CurrentVersion\CPSS\Store\IME\Bopomofo\Enable Personal Regulating\Value	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000001
HKCU\Software\Microsoft\IME\15.0\IMETC\Enable Personal Regulating	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000001
HKCU\Software\Microsoft\Windows\CurrentVersion\CPSS\Store\IME\Bopomofo\Fixed Candidate Order.New Phonetic\Value	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000000
HKCU\Software\Microsoft\IME\15.0\IMETC\Fixed Candidate Order.New Phonetic	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000000
HKCU\Software\Microsoft\IME\15.0\IMETC\Fixed Candidate Order.New Changjie	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000000
HKCU\Software\Microsoft\IME\15.0\IMETC\Fixed Candidate Order.New Quick	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000000
HKCU\Software\Microsoft\IME\15.0\IMETC\Fixed Candidate Order.Cantonese	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000000
HKCU\Software\Microsoft\Windows\CurrentVersion\CPSS\Store\IME\Bopomofo\Enable User Defined Phrases\Value	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000001
HKCU\Software\Microsoft\IME\15.0\IMETC\Enable User Defined Phrases	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000001
HKCU\Software\Microsoft\IME\15.0\IMETC\Prompt Associate Phrase.Phonetic	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000001
HKCU\Software\Microsoft\IME\15.0\IMETC\Prompt Associate Phrase.Changjie	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000001
HKCU\Software\Microsoft\IME\15.0\IMETC\Prompt Associate Phrase.Quick	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000001
HKCU\Software\Microsoft\IME\15.0\IMETC\Prompt Associate Phrase.Intelligent	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000000
HKCU\Software\Microsoft\IME\15.0\IMETC\Enable Simplified Chinese Output	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00000000
HKCU\Software\Microsoft\IME\15.0\IMETC\Keyboard Layout Setting.New Phonetic	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00020010
HKCU\Software\Microsoft\IME\15.0\IMETC\Keyboard Layout Setting.Phonetic	SUCCESS	Type: REG_SZ, Length: 22, Data: 0x00020010

## Disable feedback

`HKCU\Software\Microsoft\Siuf\Rules\NumberOfSIUFInPeriod` to `0`

## Disable cloud search

HKCU\Software\Microsoft\Windows\CurrentVersion\SearchSettings\IsMSACloudSearchEnabled	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0

## Disable AAD cloud search

HKCU\Software\Microsoft\Windows\CurrentVersion\SearchSettings\IsAADCloudSearchEnabled to `0`

## Disable search history

HKCU\Software\Microsoft\Windows\CurrentVersion\SearchSettings\IsDeviceSearchHistoryEnabled	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0

## Disable app sharing across devices
HKCU\Software\Microsoft\Windows\CurrentVersion\CDP\RomeSdkChannelUserAuthzPolicy	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0
HKCU\Software\Microsoft\Windows\CurrentVersion\CDP\CdpSessionUserAuthzPolicy	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0

## Disable lock screen slide show

HKCU\Software\Microsoft\Windows\CurrentVersion\Lock Screen\SlideshowEnabled	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0
HKCU\Software\Microsoft\Windows NT\CurrentVersion\TileDataModel\Migration\LockScreenPinnedTiles\Completed	SUCCESS	Type: REG_DWORD, Length: 4, Data: 1

## Don't show start menu recommendations

HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\Start_IrisRecommendations	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0

## Hide search in taskbar

HKCU\Software\Microsoft\Windows\CurrentVersion\Search\SearchboxTaskbarMode	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0

## Disable task view

HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\ShowTaskViewButton	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0

## Disable taskbar flashing

HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\TaskbarFlashing	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0

## Align taskbar to left

HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\TaskbarAl	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0

## Disable nearby sharing

HKCU\Software\Microsoft\Windows\CurrentVersion\CDP\SettingsPage\BluetoothLastDisabledNearShare	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0
HKCU\Software\Microsoft\Windows\CurrentVersion\CDP\NearShareChannelUserAuthzPolicy	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0
HKCU\Software\Microsoft\Windows\CurrentVersion\CDP\CdpSessionUserAuthzPolicy	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0

## Disable clipboard suggested actions

HKCU\Software\Microsoft\Windows\CurrentVersion\SmartActionPlatform\SmartClipboard\Disabled	SUCCESS	Type: REG_DWORD, Length: 4, Data: 1

## Set shell state to good

HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\ShellState	SUCCESS	Type: REG_BINARY, Length: 36, Data: 24 00 00 00 3F 28 00 00 00 00 00 00 00 00 00 00
HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\Hidden	SUCCESS	Type: REG_DWORD, Length: 4, Data: 1
HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\ShowCompColor	SUCCESS	Type: REG_DWORD, Length: 4, Data: 1
HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\HideFileExt	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0
HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\DontPrettyPath	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0
HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\ShowInfoTip	SUCCESS	Type: REG_DWORD, Length: 4, Data: 1
HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\HideIcons	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0
HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\MapNetDrvBtn	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0
HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\WebView	SUCCESS	Type: REG_DWORD, Length: 4, Data: 1
HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\Filter	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0
HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\ShowSuperHidden	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0
HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\SeparateProcess	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0
HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\AutoCheckSelect	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0
HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\IconsOnly	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0
HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\ShowTypeOverlay	SUCCESS	Type: REG_DWORD, Length: 4, Data: 1
HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\ShowStatusBar	SUCCESS	Type: REG_DWORD, Length: 4, Data: 1
HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\CabinetState\Settings	SUCCESS	Type: REG_BINARY, Length: 12, Data: 0C 00 02 00 0B 01 00 00 60 00 00 00
HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\CabinetState\FullPath	SUCCESS	Type: REG_DWORD, Length: 4, Data: 1
HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\HideDrivesWithNoMedia	SUCCESS	Type: REG_DWORD, Length: 4, Data: 0



