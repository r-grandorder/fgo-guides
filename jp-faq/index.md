# jp-faq

When editing, go to https://eb.nadeko.bot/ for a visual editor. The first block of text per section is what goes into the Description of the embed. You can copy it into the editor then replace the "description" in the 2nd block.

Right click on the original message and retrieve the message id (Right Click > Copy ID), then send the following command to Nadeko:
```
.edit #<channel-name> <message-id> <updated message>
```
For example, if you want to edit the first section in #fgo-faq
```
.edit #fgo-faq 123456 {
  "plainText": "**I) Game Startup Troubleshooting**",
  "title": "a) Terms of Service",
  "description": "ToS has been updated, pretend you read it and press `同意する`\n\n",
  "thumbnail": "https://cdn.discordapp.com/emojis/585651732617494528.gif",
  "color": 6094972,
  "image": "https://cdn.discordapp.com/attachments/610464668959375370/611198143966478376/Terms_of_Service.png"
}
```

Also update this document by sending a pull request after updating the messages (or just tell enshael the changes made).

# I) Game Startup Troubleshooting
## a) Terms of Service
```markdown
ToS has been updated, pretend you read it and press `同意する`
```
```json
{
  "plainText": "**I) Game Startup Troubleshooting**",
  "title": "a) Terms of Service",
  "description": "ToS has been updated, pretend you read it and press `同意する`\n\n",
  "thumbnail": "https://cdn.discordapp.com/emojis/585651732617494528.gif",
  "color": 6094972,
  "image": "https://cdn.discordapp.com/attachments/610464668959375370/611198143966478376/Terms_of_Service.png"
}
```

## b) Gameplay Continuation
```markdown
Your gameplay has been interrupted while story was progressing before battle. Do you want to resume from where you left off? (If you do not click resume, AP will be consumed and the story will be skipped).

`再開しない` - Don't resume
`冒頭から再開する` - Restart from the beginning
`再開する` - Resume
```
```json
{
  "title": "b) Gameplay Continuation",
  "description": "Your gameplay has been interrupted while story was progressing before battle. Do you want to resume from where you left off? (If you do not click resume, AP will be consumed and the story will be skipped).\n\n`再開しない` - Don't resume\n`冒頭から再開する` - Restart from the beginning\n`再開する` - Resume",
  "color": 6094972,
  "image": "https://cdn.discordapp.com/attachments/610464668959375370/611198179391569940/Gameplay_Continuation.png"
}
```

## c) Cached Data
```markdown
his screen usually appears after a forced close of the app before it finishes loading.
Clear Cache: No / Yes (does not affect savedata)
```
```json
{
  "title": "c) Cached Data",
  "description": "This screen usually appears after a forced close of the app before it finishes loading. \n              Clear Cache: No / Yes (does not affect savedata)",
  "color": 6094972,
  "image": "https://cdn.discordapp.com/attachments/610464668959375370/611198156461309968/Cached_Data.png"
}
```

## d) Friend/Follower Support List Usage
```markdown
`オール` : ALL
`セイバー` : SABER
`アーチャー`: ARCHER
`ランサー`: LANCER
`ライダー`: RIDER
`キャスター`: CASTER
`アサシン`: ASSASSIN
`バーサーカー` : BERSERKER
`エキストラ`: EXTRA
```
```json
{
  "title": "d) Friend/Follower Support List Usage",
  "description": "`オール` : ALL\n`セイバー` : SABER\n`アーチャー`: ARCHER\n`ランサー`: LANCER\n`ライダー`: RIDER\n`キャスター`: CASTER\n`アサシン`: ASSASSIN\n`バーサーカー` : BERSERKER\n`エキストラ`: EXTRA",
  "color": 6094972,
  "image": "https://media.discordapp.net/attachments/715302692372611143/915249108166516746/800.png"
}
```

# II) Menu Option Translations
```markdown
[a) Support List Options :BrynHug:](https://discordapp.com/channels/274980577545945090/274981376543948812/522601556164476957)
[b) Event Friend Support Filter Menu](https://discordapp.com/channels/274980577545945090/274981376543948812/707054810855374868)
[c) How To FOLLOW Someone for Story Quests :whale:](https://discordapp.com/channels/274980577545945090/274981376543948812/515741506632548362)
[d) Servant Enhancement Filter Menu](https://discordapp.com/channels/274980577545945090/274981376543948812/469104252745416704)
[e) CE Effect Filter Menu](https://discordapp.com/channels/274980577545945090/274981376543948812/558307444694974487)
[f) Present Box Filter Menu :gift:](https://discordapp.com/channels/274980577545945090/274981376543948812/492519549602889729)
[g) Extra Missions - Second tab next to Weeklies](https://discord.com/channels/274980577545945090/274981376543948812/820990975333629983)
[h) NP Speed Settings](https://discordapp.com/channels/274980577545945090/274981376543948812/504846799391948810)
[i) Servant Ascension/Sprite Settings](https://discordapp.com/channels/274980577545945090/274981376543948812/740819204772593745)
```
```json
{
  "title": "II) Menu Option Translations :flag_jp: :flag_us: ",
  "description": "[a) Support List Options :BrynHug:](https://discordapp.com/channels/274980577545945090/274981376543948812/522601556164476957)\n[b) Event Friend Support Filter Menu](https://discordapp.com/channels/274980577545945090/274981376543948812/707054810855374868)\n[c) How To FOLLOW Someone for Story Quests :whale:](https://discordapp.com/channels/274980577545945090/274981376543948812/515741506632548362)\n[d) Servant Enhancement Filter Menu](https://discordapp.com/channels/274980577545945090/274981376543948812/469104252745416704)\n[e) CE Effect Filter Menu](https://discordapp.com/channels/274980577545945090/274981376543948812/558307444694974487)\n[f) Present Box Filter Menu :gift:](https://discordapp.com/channels/274980577545945090/274981376543948812/492519549602889729)\n[g) Extra Missions - Second tab next to Weeklies](https://discord.com/channels/274980577545945090/274981376543948812/820990975333629983)\n[h) NP Speed Settings](https://discordapp.com/channels/274980577545945090/274981376543948812/504846799391948810)\n[i) Servant Ascension/Sprite Settings](https://discordapp.com/channels/274980577545945090/274981376543948812/740819204772593745)",
  "color": 6094972,
  "thumbnail": "https://cdn.discordapp.com/emojis/479359146848944131.png"
}
```
## j) Game Options ゲームオプション
```markdown
`ボリュームレベル`
Volume Levels for BGM/SFX/Voice

`テキスト表示速度`
Text Display Speed

`テキスト自動送り`
Auto Text Speed

`サポートサーヴァントの再臨状態設定の反映`
Show Servant Final Ascension Art

`サポートサーヴァントの霊衣状態の反映`
Show Servant Special Costume Art

`サポート選択画面の表示設定`
Support Selection Display Settings (Class-Advantage Default Support)

`サーヴァントの初回宝具演出等倍設定`
Normal NP Speed on First-Usage

`サーヴァントのマイルームランダム表示設定`
Set My Room Favorite Servant to Random

`フレンドのメッセージ表示設定`
Show Friend's Message

`プッシュ通知`
Push Notification for Full AP/BP

`一括ダウンロード`
Download All Data

`ブラックリストの管理`
Manage Friend Blacklist
[Friends in Blacklist won't (1) show up in your Support List or (2) be able to send you Friend Requests]

`解像度設定`: [`標準`] [`低解像度`]
Resolution setting: [Standard] [Low resolution]
(You may not be able to change to low if you are using an old phone or the game can't get accurate information about your screen resolution)

`サポートサーヴァントの霊基ネタバレ防止機能を有効にする`
Support list spoiler ascension setting
(On by default. When on it hides spoiler ascensions from support list. Note that turning it off will still hide ascensions that have additional spoiler block like Douman and Oberon's 3rd and 4th ascensions.)

`サーヴァントの再臨段階ランダムー括設定`
Random ascension setting.

`所持サーヴァント表示設定`
For yourself
(When on, all Servants you use will have random ascension. You can't change your Servants ascension settings individually while this is on.)

`フレンド&フォロー表示設定`
For friends and followers
(When on, your friends and followers will have random ascensions when using your support Servants.)

`起動時のオープニング再生`
Opening playback at startup. 
(When on, openings and PVs that you've already watched at startup will not play again.)

(Button: `初期設定に戻す` / Restore to Default Settings)
```
```json
{
  "title": "j) Game Options ゲームオプション",
  "url": "https://fategrandorder.fandom.com/wiki/Options",
  "description": "`ボリュームレベル`\nVolume Levels for BGM/SFX/Voice\n\n`テキスト表示速度`\nText Display Speed\n\n`テキスト自動送り`\nAuto Text Speed\n\n`サポートサーヴァントの再臨状態設定の反映`\nShow Servant Final Ascension Art\n\n`サポートサーヴァントの霊衣状態の反映`\nShow Servant Special Costume Art\n\n`サポート選択画面の表示設定`\nSupport Selection Display Settings (Class-Advantage Default Support)\n\n`サーヴァントの初回宝具演出等倍設定`\nNormal NP Speed on First-Usage\n\n`サーヴァントのマイルームランダム表示設定`\nSet My Room Favorite Servant to Random\n\n`フレンドのメッセージ表示設定`\nShow Friend's Message\n\n`プッシュ通知`\nPush Notification for Full AP/BP\n\n`一括ダウンロード`\nDownload All Data\n\n`ブラックリストの管理`\nManage Friend Blacklist\n[Friends in Blacklist won't (1) show up in your Support List or (2) be able to send you Friend Requests]\n\n`解像度設定`: [`標準`] [`低解像度`]\nResolution setting: [Standard] [Low resolution]\n(You may not be able to change to low if you are using an old phone or the game can't get accurate information about your screen resolution)\n\n`サポートサーヴァントの霊基ネタバレ防止機能を有効にする`\nSupport list spoiler ascension setting\n(On by default. When on it hides spoiler ascensions from support list. Note that turning it off will still hide ascensions that have additional spoiler block like Douman and Oberon's 3rd and 4th ascensions.)\n\n`サーヴァントの再臨段階ランダムー括設定`\nRandom ascension setting.\n\n`所持サーヴァント表示設定`\nFor yourself\n(When on, all Servants you use will have random ascension. You can't change your Servants ascension settings individually while this is on.)\n\n`フレンド&フォロー表示設定`\nFor friends and followers\n(When on, your friends and followers will have random ascensions when using your support Servants.)\n\n`起動時のオープニング再生`\nOpening playback at startup. \n(When on, openings and PVs that you've already watched at startup will not play again.)\n\n(Button: `初期設定に戻す` / Restore to Default Settings)",
  "color": 6094972,
  "image": "https://cdn.discordapp.com/attachments/610464668959375370/611198628089823288/Game_Options.png"
}
```

# III) Account Recovery & Backup
```markdown
[**__a) JP Account Recovery Guide - Updated 5/21/18__**](https://discordapp.com/channels/274980577545945090/274981376543948812/448031096441929728)

[**__b) Android & iOS Backup Information__**](https://discordapp.com/channels/274980577545945090/274981376543948812/585983456203374592)
```
```json
{
  "title": "III) Account Recovery & Backup",
  "description": "[**__a) JP Account Recovery Guide - Updated 5/21/18__**](https://discordapp.com/channels/274980577545945090/274981376543948812/448031096441929728)\n\n[**__b) Android & iOS Backup Information__**](https://discordapp.com/channels/274980577545945090/274981376543948812/585983456203374592)",
  "color": 6094972
}
```
#IV) Gacha Support & Troubleshooting
```markdown
[**__a) Age Verification Settings Prior to First Purchase__**](https://discordapp.com/channels/274980577545945090/274981376543948812/483313602053406720)

[**__b) FP Gacha Autoburn Settings__**](https://discordapp.com/channels/274980577545945090/274981376543948812/432041731832283146)

**__c) What are my options for purchasing Saint Quartz on FGO JP?__**

For a non-Japanese resident, your options are as follows:
__iOS__: JP iTunes Gift Cards
__Android__: Credit/Debit/Paypal/JP Google Play Gift Cards (assuming you have a Japanese Google Play account for the last option).

- Please be aware that gift cards from regions other than Japan will not work on either platform.

**__d) UPDATE [5/20/2019] : Notice regarding in-game purchases on FGO JP with Android devices/Google Play__**
- Due to a recent change in Google Play's policies that started on April 11th 2019, US, CA, UK, and AUS accounts are no longer able to use gift card balance to make purchases in apps or games only available in other countries (e.g. FGO JP). This unfortunately means that any remaining balance you have on your account from these regions will be listed as \"Not Eligible\" to be used for the Japanese version of the game. You are however, still free to use other forms of payment (credit/debit card, PayPal, bank account, etc.) available to you to complete your purchases as of the time of this writing.
```
```json
{
  "title": "IV) Gacha Support & Troubleshooting",
  "description": "[**__a) Age Verification Settings Prior to First Purchase__**](https://discordapp.com/channels/274980577545945090/274981376543948812/483313602053406720)\n\n[**__b) FP Gacha Autoburn Settings__**](https://discordapp.com/channels/274980577545945090/274981376543948812/432041731832283146)\n\n**__c) What are my options for purchasing Saint Quartz on FGO JP?__**\n\nFor a non-Japanese resident, your options are as follows:\n__iOS__: JP iTunes Gift Cards\n__Android__: Credit/Debit/Paypal/JP Google Play Gift Cards (assuming you have a Japanese Google Play account for the last option).\n\n- Please be aware that gift cards from regions other than Japan will not work on either platform.\n\n**__d) UPDATE [5/20/2019] : Notice regarding in-game purchases on FGO JP with Android devices/Google Play__**\n- Due to a recent change in Google Play's policies that started on April 11th 2019, US, CA, UK, and AUS accounts are no longer able to use gift card balance to make purchases in apps or games only available in other countries (e.g. FGO JP). This unfortunately means that any remaining balance you have on your account from these regions will be listed as \"Not Eligible\" to be used for the Japanese version of the game. You are however, still free to use other forms of payment (credit/debit card, PayPal, bank account, etc.) available to you to complete your purchases as of the time of this writing.",
  "color": 6094972,
  "image": "https://cdn.discordapp.com/attachments/610464668959375370/611198188434620418/GP_Not_Elig.jpg "
}
```

#V) Gameplay Frequently Asked Questions & Guides
```markdown
[a) Comprehensive F/GO Gameplay Guide](https://discordapp.com/channels/274980577545945090/274981376543948812/386346335554633729)

[b) Materials Drop List](https://docs.google.com/spreadsheets/d/1_SlTjrVRTgHgfS7sRqx4CeJMqlz687HdSlYqiW-JvQA/htmlview?sle=true#gid=0)

c) Material and Experience Card Calculators
<https://gamepress.gg/grandorder/servant-planner>
<https://fgosim.github.io/Material/>
<http://fgosimulator.webcrow.jp/Ember/>
- Option on top right to change Language on Material Calculator
- Webcrow is shutting down soon, if the EXP calculator is no longer working, you can try gamepress' servant planner for exp calculations 

[d) Battle Menu Translation](https://discordapp.com/channels/274980577545945090/274981376543948812/484138806321348608)

[e) NP Damage Comparison Chart](https://docs.google.com/spreadsheets/d/1OTrMARN9I06zD_jIhGdmHFWpkePoSWv_xgEk3XPzZWY/edit#gid=1993499094)

[f) NP Generation Bug Explanation & Guide :LancelotBerserker:](https://discordapp.com/channels/274980577545945090/274981376543948812/456631561186705419)

[g) \"Looping\" Servants](https://discord.com/channels/274980577545945090/801243773483876432/801253734720995378)
-> Note: Higher NP levels are necessary for these servants to work on most relevant nodes. NP1 copies will be suboptimal at best, dysfunctional at worst. 

[h) Part I Story Video Tutorials & Guides](https://discordapp.com/channels/274980577545945090/274981376543948812/385300946382487553)

[i) Part 2 Story Video Tutorials & Guides](https://www.youtube.com/playlist?list=PLwcpHdDBZvAugGUEMpQznENvt4t95wrwQ)

j) F/GO Story Fan-Translation Compilation
<https://www.reddit.com/r/grandorder/comments/6yk9ql/story_summary_compilation/>
<https://www.reddit.com/user/Volban>

[k) What are the blue cubes?](https://fategrandorder.fandom.com/wiki/Spiritvein_Stone)

[l) Why can't I do these quests?](https://discord.com/channels/274980577545945090/274981376543948812/918136416951734312)
```
```json
{
  "title": "V) Gameplay Frequently Asked Questions & Guides",
  "description": "[a) Comprehensive F/GO Gameplay Guide](https://discordapp.com/channels/274980577545945090/274981376543948812/386346335554633729)\n\n[b) Materials Drop List](https://docs.google.com/spreadsheets/d/1_SlTjrVRTgHgfS7sRqx4CeJMqlz687HdSlYqiW-JvQA/htmlview?sle=true#gid=0)\n\nc) Material and Experience Card Calculators\n<https://gamepress.gg/grandorder/servant-planner>\n<https://fgosim.github.io/Material/>\n<http://fgosimulator.webcrow.jp/Ember/>\n- Option on top right to change Language on Material Calculator\n- Webcrow is shutting down soon, if the EXP calculator is no longer working, you can try gamepress' servant planner for exp calculations \n\n[d) Battle Menu Translation](https://discordapp.com/channels/274980577545945090/274981376543948812/484138806321348608)\n\n[e) NP Damage Comparison Chart](https://docs.google.com/spreadsheets/d/1OTrMARN9I06zD_jIhGdmHFWpkePoSWv_xgEk3XPzZWY/edit#gid=1993499094)\n\n[f) NP Generation Bug Explanation & Guide :LancelotBerserker:](https://discordapp.com/channels/274980577545945090/274981376543948812/456631561186705419)\n\n[g) \\\"Looping\\\" Servants](https://discord.com/channels/274980577545945090/801243773483876432/801253734720995378)\n-> Note: Higher NP levels are necessary for these servants to work on most relevant nodes. NP1 copies will be suboptimal at best, dysfunctional at worst. \n\n[h) Part I Story Video Tutorials & Guides](https://discordapp.com/channels/274980577545945090/274981376543948812/385300946382487553)\n\n[i) Part 2 Story Video Tutorials & Guides](https://www.youtube.com/playlist?list=PLwcpHdDBZvAugGUEMpQznENvt4t95wrwQ)\n\nj) F/GO Story Fan-Translation Compilation\n<https://www.reddit.com/r/grandorder/comments/6yk9ql/story_summary_compilation/>\n<https://www.reddit.com/user/Volban>\n\n[k) What are the blue cubes?](https://fategrandorder.fandom.com/wiki/Spiritvein_Stone)\n\n[l) Why can't I do these quests?](https://discord.com/channels/274980577545945090/274981376543948812/918136416951734312)",
  "color": 6094972,
  "thumbnail": "https://cdn.discordapp.com/emojis/584722986964090883.png?size=44"
}
```
#VI) Alternatives for downloading and updating Fate/Grand Order
```markdown
Since Qooapp will no longer provide downloads/updates for Fate/Grand Order related titles, here are some alternative ways to download/update the game.

**__Apk Links__**

[Apkpure](https://apkpure.com/fate-grand-order/com.aniplex.fategrandorder)
[Tap.io](https://www.tap.io/app/434)

**__Making a Jp Google play account __*

Option 1 (requires a vpn): <https://twitter.com/carlikun/status/1295685118984687616?s=20>
Option 2 (requires a vpn): <https://www.bemanistyle.com/how-to-create-a-japanese-google-play-account-to-access-the-japanese-google-play-store/>
Option 3: <https://support.google.com/googleplay/answer/7431675?hl=en>
```
```json
{
  "title": "VI) Alternatives for downloading and updating Fate/Grand Order",
  "description": "Since Qooapp will no longer provide downloads/updates for Fate/Grand Order related titles, here are some alternative ways to download/update the game.\n\n**__Apk Links__**\n\n[Apkpure](https://apkpure.com/fate-grand-order/com.aniplex.fategrandorder)\n[Tap.io](https://www.tap.io/app/434)\n\n**__Making a Jp Google play account __*\n\nOption 1 (requires a vpn): <https://twitter.com/carlikun/status/1295685118984687616?s=20>\nOption 2 (requires a vpn): <https://www.bemanistyle.com/how-to-create-a-japanese-google-play-account-to-access-the-japanese-google-play-store/>\nOption 3: <https://support.google.com/googleplay/answer/7431675?hl=en>",
  "color": 6094972,
  "thumbnail": "https://cdn.discordapp.com/emojis/580750186247356416.gif?size=96"
}
```

#VII) Current & Future Events
```markdown
__**a) When is maintenance?**__
Check #jp-announcements, in-game news, or google it please. If it's not there then no one knows.

__**b) When is event/banner?**__ 
Check #jp-announcements, in-game news, or google it please. If it's not there then no one knows.

__**c) How do I do the event? How do I get welfare? How do I play it?**__
#jp-guides has that all covered.
```
```json
{
  "title": "VII) Current & Future Events",
  "description": "__**a) When is maintenance?**__\nCheck #jp-announcements, in-game news, or google it please. If it's not there then no one knows.\n\n__**b) When is event/banner?**__ \nCheck #jp-announcements, in-game news, or google it please. If it's not there then no one knows.\n\n__**c) How do I do the event? How do I get welfare? How do I play it?**__\n#jp-guides has that all covered.",
  "color": 6094972,
  "thumbnail": "https://cdn.discordapp.com/emojis/564283864001019924.png?size=44"
}
```

# Footer
```markdown
Check if your question is answered here before heading to #jp-help. Check the pins in #jp-help as well.
```
```json
{
  "description": "Check if your question is answered here before heading to #jp-help. Check the pins in #jp-help as well.",
  "color": 6094972,
  "image": "https://cdn.discordapp.com/attachments/715302692372611143/915259589178560542/image0.png"
}
```