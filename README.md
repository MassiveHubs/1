> [!Спасибо за покупку]
> https://funpay.com/users/7880803/

<h1 aligh="center">Вам надо иметь любой переводчие если вы плохо знаете английский! (Со временем буду переводить)</h1>

<h1 align="center"><img src="https://github.com/pizzaboxer/bloxstrap/raw/main/Images/Bloxstrap.png" width="28"/> Ultimate Fast Flags List</h1>

<h3 align="center">https://discord.gg/Q5JKyzuNRC</h3>

<h6 align="center">https://discord.gg/fastflags</h6>

##### Version: 5.0.5 [2/9/2024]
* **103 Currently Listed**
* **5 Textures Currently Listed**
* **New Formatting**
* **Removed [Bloxstrap](https://github.com/pizzaboxer/bloxstrap) Presets** <sup>Please use [Bloxstrap](https://github.com/pizzaboxer/bloxstrap)</sup>

 # How to use
* **Open the [Bloxstrap](https://github.com/pizzaboxer/bloxstrap) Menu**
* **Fast Flags >> Fast Flags Editor >> Import Json**
* **Paste in the JSON**
* **Then you should be good to go and save!**


### 

<h3 align="center">══════⊹⊱≼≽⊰⊹══════</h3>

<h1 align="center">Рендеринг API</h1>

### Metal
###### MacOS Только.
```json
{ "FFlagDebugGraphicsPreferMetal": "True" }
```
### Vulkan
```json
{ "FFlagDebugGraphicsDisableDirect3D11": "True", "FFlagDebugGraphicsPreferVulkan": "True" }
```
### OpenGL
```json
{ "FFlagDebugGraphicsDisableDirect3D11": "True", "FFlagDebugGraphicsPreferOpenGL": "True" }
```
### Direct X 10
```json
{ "FFlagDebugGraphicsPreferD3D11FL10": "True" }
```
### Direct X 11
```json
{ "FFlagDebugGraphicsPreferD3D11": "True" }
```

<h1 align="center">Графические настройки И другие штуки</h1>

### Гладкая растительность (Иммею ввиду земля)
```json
{ "FFlagDebugRenderingSetDeterministic": "True" }
```
### 😍
```json
{ "FFlagDebugLuaHeapDump": "True" }
```
### Графический уровень качества (Можно поставить в настройках роблокса)
```json
{ "FIntRomarkStartWithGraphicQualityLevel": "1" }
```
### Низко качественные текстуры растительности (Иммею ввиду земля)
###### 4 для меньшего качества 16, 32, 64 для большего качевства
```json
{ "FIntTerrainArraySliceSize": "4" }
```
### Отключить тени
```json
{ "FIntRenderShadowIntensity": "0" }
```
### FPS Лимит
```json
{ "DFIntTaskSchedulerTargetFps": "9999" }
```
### Включает отладку сети треккеров.
##### Инструкции: CTRL+F8
```json
{ "DFFlagDebugEnableInterpolationVisualizer": "True" }
```
### Humanoid Outline
##### Draws an outline around every part and every humanoid
```json
{ "DFFlagDebugDrawBroadPhaseAABBs": "True" }
```
### Buggy ZPlane Camera *<sup>a.k.a xray</sup>*
```json
{ "FIntCameraFarZPlane": "1" }
```
### Preserve rendering quality with display setting
```json
{ "DFFlagDisableDPIScale": "True" }
```
### Low Graphics Quality w/ Max Render Distance
###### Explanation: 1-6 Are low graphics, Above 6 are high graphics. Like the 1-21 graphics slider
```json
{ "DFIntDebugFRMQualityLevelOverride": "1" }
```

<h4 align="center">FRM Levels</h4>

```
Low

1 = 3
2 = 2
3 = 6

High

4 = 7
5 = 11
6 = 14
7 = 15 
8 = 17
9 = 18
10 = 21
```

### Низкая прорисовка дальности (Как в майнкрафте чанки.)
###### [FRM](https://github.com/devstacking/Epic-Fast-Flags-List?tab=readme-ov-file#frm-levels)
```json
{ "DFIntDebugRestrictGCDistance": "1" }
```
### Отключить ветер
```json
{ "FFlagGlobalWindRendering": "False", "FFlagGlobalWindActivated": "False" }
```
### Limits light updates
```json
{ "FIntRenderLocalLightUpdatesMax": "8", "FIntRenderLocalLightUpdatesMin": "6" }
```
### Disables fade in and fade out animation every light update
###### changes fade in ms!!
```json
{ "FIntRenderLocalLightFadeInMs": "0" }
```
### Делает аватар блестящем.
###### [everything goes black on <3] ***[DFIntDebugFRMQualityLevelOverride is there to set your graphics to 10, You can change it to anything above 3: [Click here to view](https://github.com/devstacking/Epic-Fast-Flags-List?tab=readme-ov-file#frm-levels) ]***
```json
{ "DFIntRenderClampRoughnessMax": "-640000000", "DFIntDebugFRMQualityLevelOverride": "21" }
```
### Отключить пост обработку
```json
{ "FFlagDisablePostFx": "True" }
```
### Pause Voxelizer/Disable Baked Shadows
```json
{ "DFFlagDebugPauseVoxelizer": "True" }
```
### Серое небо
```json
{ "FFlagDebugSkyGray": "True" }
```
### Отключить тени игрока
```json
{ "FIntRenderShadowIntensity": "0" }
```
### Force LOD on Meshes
```json
{ "DFIntCSGLevelOfDetailSwitchingDistance": "0", "FFlagGlobaDFIntCSGLevelOfDetailSwitchingDistanceL12lWindActivated": "0", "DFIntCSGLevelOfDetailSwitchingDistanceL23": "0", "DFIntCSGLevelOfDetailSwitchingDistanceL34": "0" }
```
### Lighting Attenuation
```json
{ "FFlagNewLightAttenuation": "True" }
```
### Enable GPULightCulling
###### Combine with [Lighting Attenuation](https://github.com/devstacking/Epic-Fast-Flags-List?tab=readme-ov-file#lighting-attenuation) for better vision
```json
{ "FFlagFastGPULightCulling3": "True" }
```
### Frame Buffer
###### Explnation: 0 makes white screen 1-3 makes other players have laggy movement, 4 is stable has better performance than 10 and less input lag
```json
{ "DFIntMaxFrameBufferSize": "4" }
```
### High Quality Textures 
###### *[1-3]*
```json
{ "DFFlagTextureQualityOverrideEnabled": "True", "DFIntTextureQualityOverride": "3" }
```
### Lower Quality Textures 
###### *[1-3]*
```json
{ "DFIntPerformanceControlTextureQualityBestUtility": "-1" }
```
### Убрать траву
```json
{ "FIntFRMMinGrassDistance": "0", "FIntFRMMaxGrassDistance": "0", "FIntRenderGrassDetailStrands": "0", "FIntRenderGrassHeightScaler": "0" }
```
### Force MSAA 
###### *[0, 1, 2, 4, 8]*
```json
{ "FIntDebugForceMSAASamples": "4" }
```
### ShadowMap Bias 
###### ***[Future & ShadowMap]***
```json
{ "FIntRenderShadowmapBias": "75" }
```
<h1 align="center">User Interface</h1>

### Не прозречное V4 меню (На кнопку esc) **(2023)**
```json
{ "FStringInGameMenuModernizationStickyBarForcedUserIds": "UserID" }
```

### Revert Old Report Menu
```json
{ "FStringReportAbuseMenuRoactForcedUserIds": "UserID_HERE", "FFlagEnableReportAbuseMenuRoactABTest2": "False", "FFlagEnableReportAbuseMenuRoact2": "False", "FFlagEnableReportAbuseMenuLayerOnV3": "False" }
```

### Custom MicroProfile Scale
```json
{ "DFIntMicroProfilerDpiScaleOverride": "100" }
```

### V1 меню
```json
{ "FIntNewInGameMenuPercentRollout3": "10000" }
```
### Hides gui
```json
{ "FFlagDebugAdornsDisabled": "True" }
```
### Dont Render UI
```json
{ "FFlagDebugDontRenderUI": "True" }
```
### Enable Audio Controller
```json
{ "FFlagTrackerLodControllerDebugUI": "True" }
```
### Disable Autocomplete
```json
{ "FFlagEnableCommandAutocomplete": "False" }
```
### Chrome UI TopBar
```json
{ "FFlagEnableInGameMenuChrome": "True" }
```
### Better Chrome UI TopBar
```json
{ "FFlagChromeBetaFeature": "True", "FFlagEnableChromePinnedChat": "True", "FFlagEnableInGameMenuChrome": "True", "FFlagEnableInGameMenuChromeABTest": "True", "FFlagEnableInGameMenuChromeSignalAPI": "True", "FFlagPlayerListChromePushdown": "True", "FFlagEnableChromeEscapeFix": "True", "FFlagEnableChromeMicShimmer": "True", "FFlagPlayerListChromePushdown": "True" }
```
### Chrome UI Topbar Removal
```json
{ "FFlagChromeBetaFeature": "False", "FFlagEnableChromePinnedChat": "False", "FFlagEnableInGameMenuChrome": "False", "FFlagEnableInGameMenuChromeABTest": "False", "FFlagEnableInGameMenuChromeSignalAPI": "False", "FFlagPlayerListChromePushdown": "False" }
```
### Disable Bubble Chat
```json
{ "FFlagEnableBubbleChatFromChatService": "False" }
```
### Disable Selfview
```json
{ "FFlagCoreGuiTypeSelfViewPresent": "False" }
```
### Remove VC Beta Badge
```json
{ "FFlagVoiceBetaBadge": "False", "FFlagTopBarUseNewBadge": "False", "FFlagEnableBetaBadgeLearnMore": "False", "FFlagBetaBadgeLearnMoreLinkFormview": "False", "FFlagControlBetaBadgeWithGuac": "False", "FStringVoiceBetaBadgeLearnMoreLink": "null" }
```
### Pin Chat on Chrome UI
```json
{ "FFlagEnableChromePinnedChat": "True" }
```
### Hide guis
###### ***Instructions: Replace "ID" with any group ID that you are in.***
```json
{ "DFIntCanHideGuiGroupId": "ID_HERE" }
```
### Disable Fullscreen Title Bar
```json
{ "FIntFullscreenTitleBarTriggerDelayMillis": "3600000" }
```
### Set Custom Font Size
```json
{ "FIntFontSizePadding": "1" }
```

<h1 align="center">Textures</h1>

### No Textures
```json
{
    "FStringPartTexturePackTable2022": "{\"glass\":{\"ids\":[\"rbxassetid://9873284556\",\"rbxassetid://9438453972\"],\"color\":[254,254,254,7]}}",
    "FStringPartTexturePackTablePre2022": "{\"glass\":{\"ids\":[\"rbxassetid://7547304948\",\"rbxassetid://7546645118\"],\"color\":[254,254,254,7]}}",
    "FStringTerrainMaterialTable2022": "",
    "FStringTerrainMaterialTablePre2022": ""
}
```

### Others moved to [Textures Branch](https://github.com/devstacking/Epic-Fast-Flags-List/tree/textures)

<h1 align="center">Physics</h1>

### Stick unanchored parts to you
###### - = up, + = down
###### blame popbob he said it was ok to leak this
```json
{ "DFIntSolidFloorPercentForceApplication": "-1000", "DFIntNonSolidFloorPercentForceApplication": "-5000" }
```
### Breaks glitches stuff
###### All type of wallhops, longjumps, headhitters and probably more stop working
```json
{ "DFFlagSimHumanoidPhysics": "True" }
```
### Max Raycast Distance
###### Break legs collision from 2 to -inf, kinda break camera on values over 3
###### noclip cam on 3
```json
{ "DFIntRaycastMaxDistance": "3" }
```
### Possible Super Jump
###### i thought this was patched thats why i removed it lol
```json
{ "DFIntNewRunningBaseGravityReductionFactorHundredth": "1500" }
```
### Breaks movement on higher negative values
```json
{ "FIntPGSAngularDampingPermilPersecond": "-10000" }
```
### it does something to movement cant describe rn cus im busy
```json
{ "FIntPGSAngularDampingPermilPersecond": "0" }
```
### It allows you to fall quicker and ignore certain block designs
```json
{ "FFlagHumanoidOnlySetCollisionsOnStateChangeDefaultIsEnabled": "False", "FFlagHumanoidParallelFasterSetCollision": "True" }
```
### Gear Desync
###### a.k.a dos not let you load games
```json
{ "DFIntDataSenderRate": "-1" }
```
### Fake Lag
```json
{ "DFIntS2PhysicsSenderRate": "1" }
```
### ultiamt desync flag!! 😱😱😱
```json
{ "DFIntS2PhysicsSenderRate": "1", "FIntPGSAngularDampingPermilPersecond": "0" }
```
### Noclip 1
###### adjust the value so u dont fall through the ground
```json
{ "DFFlagAssemblyExtentsExpansionStudHundredth": "-50" }
```
### Noclip 2
```json
{
{ "FIntPGSPenetrationMarginMax": "2147483647", "FIntPGSPenetrationMarginMin": "2147483647" }
```
### Noclip Combo
###### adjust the value so u dont fall through the ground
```json
{ "FIntPGSPenetrationMarginMax": "2147483647", "FIntPGSPenetrationMarginMin": "2147483647", "DFFlagAssemblyExtentsExpansionStudHundredth": "-50" }
```
### Teleportation
###### a.k.a control the unanchored
```json
{ "FIntPGSPenetrationMarginMax": "-100000000", "FIntPGSPenetrationMarginMin": "-100000000" }
```
### limited speed fflag that works only in a few games
###### one of them being Phantom Forces, and it makes you only slightly faster
```json
{ "DFIntDebugSimPhysicsSteppingMethodOverride": "10000000" }
```
### Hip Height
###### Very controllable bounce, only works with negative values, 0 allows you to hover
```json
{ "DFIntMaxAltitudePDStickHipHeightPercent": "-200" }
```
### Wallglide
```json
{ "DFFlagUnstickForceAttackInTenths": "-4" }
```

<h1 align="center">other fflags</h1>

### Disable ADs
```json
{ "FFlagAdServiceEnabled": "False" }
```

### Disable Telemetry 
###### *[This doesn't fully disable telemetry]*
```json
{ "FFlagDebugDisableTelemetryEphemeralCounter": "True", "FFlagDebugDisableTelemetryEphemeralStat": "True", "FFlagDebugDisableTelemetryEventIngest": "True", "FFlagDebugDisableTelemetryPoint": "True", "FFlagDebugDisableTelemetryV2Counter": "True", "FFlagDebugDisableTelemetryV2Event": "True", "FFlagDebugDisableTelemetryV2Stat": "True" }
```
### Scroll Speed
```json
{ "FIntScrollWheelDeltaAmount": "140" }
```
### Surf the web inside of Roblox
###### Click the Beta badge or the 13+ badge to open the webview browser.
```json
{ "FFlagTopBarUseNewBadge": "True", "FStringTopBarBadgeLearnMoreLink": "https://google.com/", "FStringVoiceBetaBadgeLearnMoreLink": "https://google.com/" }
```
### Sounds use physical velocity and become distorted
```json
{ "FFlagSoundsUsePhysicalVelocity": "True" }
```
### Shows the state of a flag
```json
{ "FStringDebugShowFlagState": "FLAG_HERE" }
```
###### e.g
```json
{ "FStringDebugShowFlagState": "DFIntTaskSchedulerTargetFps, ChannelName" }
```
### MTU 
###### ***[Might Improve Ping]***
```json
{ "DFIntConnectionMTUSize": "MTU_HERE" }
```
### No Internet Disconnect 
###### *[You will still be kicked but the message wont show.]*
```json
{ "DFFlagDebugDisableTimeoutDisconnect": "True" }
```
### Quick Game Launch 
###### *[BUGGY]*
```json
{ "FFlagEnableQuickGameLaunch": "True" }
```
### Allows you to change voice chat distance 
###### default: [Min 7 Max 80]
```json
{ "DFIntVoiceChatRollOffMinDistance": "7", "DFIntVoiceChatRollOffMaxDistance": "80" }
```
### Disable In-Game Purchases
```json
{ "DFFlagOrder66": "True" }
```
### Disable Chat
```json
{ "FFlagDebugForceChatDisabled": "True" }
```
### Limit audios that are being played
```json
{ "DFIntMaxLoadableAudioChannelCount": "1" }
```
### Adds an UI in game, which highlights any part player touches (like ground, Meshes etc.). It's a non-functioning UI too. Also adds a blue circle to your humanoid.
```json
{ "FFlagDebugHumanoidRendering": "True" }
```
### Custom Disconnect Message
```json
{ "FFlagReconnectDisabled": "True", "FStringReconnectDisabledReason": "You're stupid and I hate you" }
```
### Display FPS
```json
{ "FFlagDebugDisplayFPS": "True" }
```
### Verified Badge
```json
{ "FStringWhitelistVerifiedUserId": "UserID_HERE" }
```
### Verified Badge on everyone
```json
{ "FFlagOverridePlayerVerifiedBadge": "True" }
```
### Applies cool colors to stuff
```json
{ "FFlagDebugDisplayUnthemedInstances": "True" }
```
### Show Outlined Chunks
```json
{ "FFlagDebugLightGridShowChunks": "True" }
```
### Remove Disconnect Blur/Loading Blur
```json
{ "FIntRobloxGuiBlurIntensity": "0" }
```
### Disable Dynamic Heads Animations
```json
{ "DFFlagEnableDynamicHeadByDefault": "False" }
```
### failsafehumanoid
###### gray avatars
```json
{ "FFlagFailsafeHumanoid_3": "True" }
```
### Automatically unmutes your mic on join
```json
{ "FFlagDebugDefaultChannelStartMuted": "False" }
```
### Overlay that shows what you type 
```json
{ "FFlagDebugTextBoxServiceShowOverlay": "True" }
```
### opt-out Experience Language
###### Removes the Experience Language option in settings
```json
{ "FIntV1MenuLanguageSelectionFeaturePerMillageRollout": "0" }
```
### Disable New Chat Translation Settings
```json
{ "FFlagChatTranslationSettingEnabled3 ": "False" }
```
### Lets you change the zoom out limit
###### infinite zoom out!!
```json
{ "FIntCameraMaxZoomDistance": "9999" }
```
### Limits number of animations being played
```json
{ "DFIntMaxActiveAnimationTracks": "0" }
```
### Prevents Remote Events from running
###### W SPECTRO
```json
{ "DFIntRemoteEventSingleInvocationSizeLimit": "1" }
```
### Clientsided Invisible
```json
{ "FIntParallelDynamicPartsFastClusterBatchSize": "1" }
```

<h1 align="center">Links</h1>

### [Make Your Own Custom Roblox Textures](https://github.com/GoingCrazyDude/roblox-custom-textures/blob/main/README.md) *[Github Repo Link]*
### [Bloxstrap](https://github.com/pizzaboxer/bloxstrap) *[Github Repo Link]*
### [NVIDIA Shaders Guide](https://github.com/catb0x/Roblox-Shaders-Guide) *[Github Repo Link]*
### [EnableAnselForRoblox](https://github.com/DED0026/EnableAnselForRoblox) *[Github Repo Link]*


### Patched in 0, 608, 1, 6080485
```
DFIntFreeFallBalanceP 
DFIntFreeFallOrientationP
DFIntGettingUpBalanceD
DFIntGettingUpBalanceP
DFIntLandedBalanceD
DFIntLandedBalanceP
DFIntNewRunningBaseAltitudeD
DFIntNewRunningBaseAltitudeP
DFIntRunningBaseAltitudeD
DFIntRunningBaseAltitudeP
DFIntRunningBaseOrientationP
FFlagDebugSimIntegrationStabilityTesting
FFlagSimIslandizerManager
```

<h4 align="center">‧⁺̣˚̣̣*̣̩⋆̩·̩̩୨˚̣̣̣̣͙୧·̩̩⋆̩*̣̩˚̣̣⁺̣‧ You've reached the bottom of the list! ‧⁺̣˚̣̣*̣̩⋆̩·̩̩୨˚̣̣̣̣͙୧·̩̩⋆̩*̣̩˚̣̣⁺̣‧୨</h4>


