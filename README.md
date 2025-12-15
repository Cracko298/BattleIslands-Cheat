## BattleIslands Cheat:
- Repo made for [this video](https://youtu.be/8Hj9zHmGeqM?si=LzEwzcLg2OqiJhN6).
- A simple cash cheat without the shady sites.

## Note
- This is a xdelta3 patch, as such you'll need to patch your game manually (`Assembly-CSharp.dll`).

## Installing (PC):
1. Download the Patch [Here (PC)](https://github.com/Cracko298/BattleIslands-Cheat/raw/refs/heads/main/BattleIslands_MoneyPatch_PC.xdelta) and the [Delta Patcher](https://github.com/marco-calautti/DeltaPatcher/releases/latest) for your System.
2. Extract the Delta Patcher, run the Patcher executable.
3. Select the `*.xdelta` patch you downloaded, and apply it to your Unmodified `Assembly-CSharp.dll` file.
   - `BISTEAM_ROOT\BattleIslands_Data\Managed\Assembly-CSharp.dll` **NOT** `Assembly-CSharp-firstpass.dll`.
4. That's about it, it should work perfectly fine now, and you'll never lose money in-game.

## Installing (Android/Mobile):
1. Download the Patch [Here (Mobile)](https://github.com/Cracko298/BattleIslands-Cheat/raw/refs/heads/main/BattleIslands_MoneyPatch_MOBILE.xdelta) and the [Delta Patcher](https://github.com/marco-calautti/DeltaPatcher/releases/latest) for your System.
2. Extract the Delta Patcher, run the Patcher executable.
3. Select the `*.xdelta` patch you downloaded, and apply it to your Unmodified `Assembly-CSharp.dll` file (use [APKTool](https://apktool.org/docs/install)).
   - `APK_ROOT\assets\bin\Data\Managed\Assembly-CSharp.dll` **NOT** `Assembly-CSharp-firstpass.dll`.
4. You will need to Re-Package your APK using [APKTool](https://apktool.org/docs/install), [Zip-Align](https://developer.android.com/tools/zipalign), then use [Apk-Signer](https://developer.android.com/tools/apksigner) to Sign the APK Executable.
   - This guide does **NOT** go into Re-Packaging these APKs. A quick *Google Search* or Inquery via ChatGPT should yeild the answers (Different for Everybody).
