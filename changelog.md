### v2.3.6
- Improved compatibility with other bot's macros (Pathfinder, Eclipse).

### v2.3.5
- Added render warning.
- Fixed clickbot not working.
- Fixed render audio recording bugs.
- Fixed auto save on level end not working.

### v2.3.4
- Fixed render green video issue.

### v2.3.3
- Fixed Android render input length being limited to 3.
- Fixed macro auto-saving on level end even if auto-save was not enabled.

### v2.3.2
- Fixed Android default render codec.
- Fixed Android width input length being limited to 3.
- Fixed macros folder not creating automatically if missing.
- Fixed song file not found on Android render (it can't handle audio).

### v2.3.1
- Fixed renders folder not creating automatically if missing.

### v2.3.0
- Added TPS Bypass.
- Added Android Renderer support with FFmpeg API.
- Added autoclicker.
- Added Clickbot "Hold Only" setting.
- Added auto-disable speedhack setting.
- Added inverted mirror input setting.
- Added macros save folder setting.
- Added autosaves folder setting.
- Added Input Fixes setting.
- Added Frame Fixes Limit setting.
- Added restore button in Android button edit layer.
- Added warning when disabling a button in the pause menu.
- Added auto save on level end.
- Added auto save on time interval.
- Fixed Clickbot ignoring clicks on the same frame.
- Fixed 2-player macro bugs with "flip 2 player controls."
- Fixed crash when renders folder path was invalid.
- Fixed BetterInputs incompatibility.
- Fixed render volume setting not working in legacy audio mode.
- Fixed Disable Shaders working unexpectedly.
- Fixed input bug when resuming pause with space bar.
- Fixed macro merge not working properly.
- Fixed crash with invalid macro files.
- Fixed layout mode crash in certain levels using particles.
- Fixed Android crash on edit macro.
- Fixed Android speedhack only allowing 1 decimal digit.
- Removed leftover debug logs.
- Removed keybinds button warning.
- Improved random seed generation.
- Improved Clickbot performance.
- Improved render hide level complete setting.
- Changed Clickbot default sounds.
- Changed render default codec and codec popup.
- Swapped positions of SFX and music volume in render settings.
- Changed Discord server popup message.
- Re-added .gdr save toggle.
- Re-added xdBot menu button in mod settings.
- Moved Show Trajectory extra settings to its own UI.
- Moved Auto Stop Playing and Lock Delta settings to more options.
- Optimized some features.
- Made settings page save after reopening.
- Made disable shaders trigger auto safe mode.
- Made auto-saved macros have descriptions.
- Slightly changed extra hack settings button appearance.

### v2.2.6
- Fixed Discord link.

### v2.2.5
- Discord update.

### v2.2.4
- Fixed render fade out not re-encoding with the original bitrate.
- Miscellaneous fixes.

### v2.2.3
- General fixes.

### v2.2.2
- Fixed layout mode returning "Load Failed!" on RobTop levels.
- Fixed crazy layout mode bug.
- Fixed render arguments not allowing certain characters.
- Fixed fade out not re-encoding with the selected codec.
- Fixed render restore defaults button not working.
- Added render file extension setting.
- Added render info popups for audio settings.
- Renamed render "Only Add Song" to "Legacy Audio".

### v2.2.1
- Added renders folder button back, but inside the render presets menu.
- Added pause retention while recording audio.
- Made render audio recording stop when the player dies.
- Fixed dash trail looking weird with show trajectory on.
- Fixed render audio recording not stopping on 60fps.
- Fixed render fade out not working.
- Fixed being able to type anything in fade inputs.
- Fixed render not working when fade out time exceeded video length.

### v2.2.0
- Changed default restore page setting.
- Fixed play button sound appearing in renders.
- Fixed keybinds button opening mobile keybinds on PC.
- Fixed render width and height inputs being low opacity for some users.
- Fixed follow trigger bug (might break some macros in Timewarp).
- Added render fade in and fade out.
- Added render volume settings.
- Added render hide endscreen setting.
- Added render hide level complete setting.
- Added render presets.
- Added trajectory on both sides setting.
- Added input mirror.
- Added disable shaders.
- Added instant mirror portal.
- Added no mirror portal.
- Added custom respawn time.
- Added lock delta (filler).
- Added optional button in level settings.
- Added Ko-Fi link.

### v2.1.3
- Fixed GUI issues.

### v2.1.2
- Made BetterInputs warning appear only once.

### v2.1.1
- Updated to Geode 4.0.0-beta.1.

### v2.1.0
- Update 2.207.

### v2.0.3
- Fixed render audio desync.

### v2.0.2
- Added render audio record.
- Improved render shaders.
- Made it possible to continue platformer macros.

### v2.0.1
- Fixed crash if some macro info was null.
- Fixed macro bot info saving bug.
- Fixed practice rotation bug.
- Capped render FPS to 240.

### v2.0.0
- Increased render FPS cap to 240.
- Increased speedhack limit to 10.
- Changed frame offset setting limit to 8.
- Updated render error ID 12 message.
- Made speedhack work everywhere.
- Fixed macros importing as .gdr instead of .gdr.json.
- Added warning when rendering if CBF is loaded.
- Added render save location setting.

### v2.0.0-beta.7
- Fixed show trajectory and spider flip bugs.

### v2.0.0-beta.6
- Fixed popup brown color and search macro crash.
- Added recording-only keybinds setting.
- Added fade in and fade out to render videos.

### v2.0.0-beta.5
- Fixed render restore defaults button setting wrong args.
- Fixed crash on level complete with practice attempts installed.
- Improved auto safe mode text visibility.

### v2.0.0-beta.4
- Fixed dual bug when replaying a macro.
- Fixed inability to import .json macros.

### v2.0.0-beta.3
- Fixed rotation bug and crash on macro load.
- Added Alt modifier to default keybinds.

### v2.0.0-beta.2
- A bunch of minor changes.

### v2.0.0-beta.1
- Removed NodeIDs dependency.

### v2.0.0-alpha.14
- Fixed Click on Steps incompatibility.

### v2.0.0-alpha.13
- Fixed Macro Editor and Noclip Settings popups not changing color.

### v2.0.0-alpha.12
- Fixed speedhack bug and added Noclip settings.

### v2.0.0-alpha.11
- Fixed shader toggle bug.
- Added Macro Editor and incompatibility warnings.

### v2.0.0-alpha.10
- Fixed crash when recording or playing a macro.

### v2.0.0-alpha.9
- Removed tps bypass detector and added Prism Menu TPS bypass incompatibility.

### v2.0.0-alpha.8
- Fixed freezing when recording in platformer mode and opening menu crash.

### v2.0.0-alpha.7
- Fixed QOLMod TPS bypass detector.

### v2.0.0-alpha.6
- Fixed issues related to loading layers, clicking, and TPS/Physics bypass.

### v2.0.0-alpha.5
- Fixed various crashes and layout mode bugs.

### v2.0.0-alpha.4
- Fixed several UI bugs and added speedhack/coin finder to auto-safe mode.

### v2.0.0-alpha.3
- Fixed crash on Android when respawning from checkpoint.

### v2.0.0-alpha.2
- Fixed percentage bug, checkpoint restart issues, and macro syncing bugs.

### v2.0.0-alpha.1
- Completely rewrote the bot. Added new features like auto-saving, renderer, and customizable keybinds.

### v1.6.1
- Geode 3.0.0 beta 1.

### v1.6.0
- Frame fixes for Android.
- PC macros now work on Android.

### v1.5.5
- Fixed spider animation not showing with frame fixes.

### v1.5.4
- Added layout mode and improved Android safe mode.

### v1.5.3
- Fixed settings button issues and player death bug.

### v1.5.2
- Removed Discord.

### v1.5.1
- Disabled Ignore Inputs on Android temporarily.

### v1.5.0
- Added several new settings like NoClip, Instant Respawn, and Auto Safe Mode.

### v1.4.8
- Fixed Android macro bugs.

### v1.4.7
- Fixed speedhack audio staying on after macro play.

### v1.4.6
- Fixed occasional restart crash.

### v1.4.5
- Fixed Android macros crashing.

### v1.4.4
- Fixed Android macros recording incorrectly.

### v1.4.3
- Re-worked FPS selector and fixed some Android issues.

### v1.4.2
- Added FPS selector and fixed Android key issues.

### v1.4.1
- Fixed various bugs and alignment issues with Android buttons.

### v1.4.0
- Added Android support and other improvements.

### v1.3.10
- Fixed macro behavior changes.

### v1.3.9
- Fixed crash and macro recording over issues.

### v1.3.8
- Fixed occasional crash on restart.

### v1.3.7
- Added bugs and fixed a mysterious one.

### v1.3.6
- Air update.

### v1.3.5
- Fixed issues with macro saving and deletion.

### v1.3.4
- Fixed practice mode restart crash and other macro issues.

### v1.3.3
- Added override macro mode setting.

### v1.3.2
- Fixed macro list order and version label on menu.

### v1.3.1
- Fixed input and frame fix modes, added new settings.

### v1.3.0
- Removed "Lock Delta" and added new macro and frame fixes.

### v1.2.1
- Added forced safe mode for playing macros.

### v1.2.0
- Added speedhack shortcut and frame stepper.

### v1.1.1
- Bug fixes.

### v1.1.0
- Added speedhack and lock delta.

### v1.0.2
- Reworked macro saving/loading system.

### v1.0.12
- Fixed teleport orb and geode version targeting.

### v1.0.1
- Fixed GUI issues and improved macro recording.

### v1.0.0
- First release.
