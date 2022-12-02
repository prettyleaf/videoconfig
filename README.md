# Apex Legends Season 15 Video Configs

<p align="center">
  <a href="https://www.donationalerts.com/r/pr3ttyleaf">
  <img src="https://img.shields.io/badge/Sponsor-blue?logo=github-sponsors&style=for-the-badge&color=grey">
</a> 
</p>

## Apex Legends videoconfig based on performance improvement.

- Please remove preset name argument in file name to make it work in-game.
- Please make sure you have checked the "Read-only" box in the file properties before launching the game.

## Installation

- How to make it work? Put ``videoconfig.txt`` in the directory:

    ```
    C:\Users\%User%\Saved Games\Respawn\Apex\local
    ```
- Please remove preset name argument in file name to make it work in-game.
- Please make sure you have checked the "Read-only" box in the file properties before launching the game.   
- Also try importing an [autoexec](https://github.com/Rockstar234/autoexec)
## What does the strings and numbers mean? What Changed? (Advanced users)
You may edit the config for your needs, but nobody else expect you will take a responsibility for it.

- Custom Texture Resolution

    ```
    "setting.stream_memory"		"0"
    ```
    
- Texture Compression. Put 4 if ``setting.stream_memory = 0``, else put 2
    ```
    "setting.mat_picmip"		"4"
    ```
- Shadows are recommended to be turned off, because you don't actually turn them off
    
    ```
    "setting.shadow_enable"		"0"
    ```
- SSAO

    ```
    "setting.ssao_enabled"		"0"
    ```

- The real one shadows. Change ``settings.csm_enabled`` to 1 if you're playing on DX11

    ```
    "setting.csm_enabled"		"0"
    "setting.csm_coverage"		"0"
    "setting.csm_cascade_res"		"0"
    ```
    
- Shadows settings. Not really sure what does it change

   ```
   "setting.new_shadow_settings"		"1"
   ```

---

## 🍰 **Supporters and donators**

<a href="https://github.com/Rockstar234/autoexec">
  <img alt="@Rockstar234/autoexec's brand logo without text" align="right" src="https://cdn.discordapp.com/emojis/946448229690671144.webp?size=96&quality=lossless" width="18%" />
</a>

We are currently looking for new donators to help and maintain this project! ❤️

By donating, you will help the development of this project, and *you will be featured in this project's README.md*, so everyone can see your kindness and visit your content ⭐.

<a href="https://www.donationalerts.com/r/pr3ttyleaf">
  <img src="https://img.shields.io/badge/Sponsor-Rockstar234/autoexec-blue?logo=github-sponsors&style=for-the-badge&color=red">
</a>
