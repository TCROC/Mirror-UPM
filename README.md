# New Repository

https://github.com/TCROC/Mirror-Submodule

## Reasons

1. Unity had a TOS update for use of UPM and I'm not exactly sure what that means for open source projects.  Submodules feel safer.  More can be read here. [here](https://forum.unity.com/threads/updates-to-our-terms-of-service-and-new-package-guidelines.999940/).

2. I could not get UPM get to work properly in Unity 2020 LTS.  The git submodules work perfectly tho!

I'll be archiving this repository, but feel free to use the other one! :)

# Mirror-UPM

This repo runs nightly and formats Mirror releases for UPM.  The Mirror repo can be found here: https://github.com/vis2k/Mirror.

# How To Use

- [UPM Git Extension](https://github.com/mob-sakai/UpmGitExtension) (Recommended)
- [UPM Git Dependency](https://docs.unity3d.com/Manual/upm-git.html)
  - To pull the latest upm release:
    ```
    https://github.com/TCROC/Mirror-UPM.git#releases/upm
    ```
  - To pull a tagged version:
    ```
    https://github.com/TCROC/Mirror-UPM.git#[insert tag here]
    ```
    - Example:
      ```
      https://github.com/TCROC/Mirror-UPM.git#19.1.2
      ```
# Reporting Issues

If you find any issues please open up an issue so it can be fixed :)

# Contributing

If you want to contribute, just fork this repo and create a PR to the dev branch when you are happy with your changes.
