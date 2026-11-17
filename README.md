<!-- DRAFT for github.com/danielcorredorm/UnrealEngine-Times_Curse — not part of the website build.
     Copy it to the repo root as README.md (it replaces the one-line "# UnrealEngine").
     Everything here was read from the repo's own source and config and from the Projects page of the site. -->

# Time's Curse — course project (Unreal Engine 4.24, C++)

[![Gameplay video](https://img.youtube.com/vi/XsVKexYAbGo/hqdefault.jpg)](https://youtu.be/XsVKexYAbGo)

My own single-player third-person game, built during the course *Video Game Development in Unreal Engine* (Arkde, 2020). Each class taught a technique, and I used it my own way in this game. The Unreal project is still named `Homework`, from the course.

**More projects:** https://danielcorredorm.dev/projects/

## What is in it

| System | Where |
|---|---|
| Melee combos driven by Anim Notifies and Anim Notify States (combo windows, per-hit enable and disable) | [`Animations/Character`](Source/Homework/Public/Animations/Character) |
| Ranged weapons: rifle, grenade launcher and pad launcher, on a shared weapon base | [`Weapon/`](Source/Homework/Public/Weapon) |
| Enemies with an AI controller, patrol paths, a bot enemy and a bot spawner | [`Enemy/`](Source/Homework/Public/Enemy) |
| Health component shared by the player and enemies, with enemy health bars | [`Components/HW_HealthComponent`](Source/Homework/Public/Components/HW_HealthComponent.h), [`UI/Enemy`](Source/Homework/Public/UI/Enemy) |
| Level objects: doors and keys, mines, launch pads, barrels, health boxes, victory zone | [`Source/Homework/Public`](Source/Homework/Public), [`Items/`](Source/Homework/Public/Items) |
| Save system | [`SaveSystem/HW_SaveGame`](Source/Homework/Public/SaveSystem/HW_SaveGame.h) |
| HUD with objectives, health, an enemy counter and an ultimate; main and pause menus | [`UI/`](Source/Homework/Public/UI) |
| Cheat manager for testing | [`Core/HW_CheatManager`](Source/Homework/Public/Core/HW_CheatManager.h) |

## Build and play

1. Unreal Engine **4.24** and Visual Studio with the C++ game development workload.
2. Right-click `Homework.uproject` → **Generate Visual Studio project files**, build **Development Editor | Win64**, then open the project. It starts on the `MainMenu` map.

| Action | Key |
|---|---|
| Move / look | WASD / mouse |
| Weapon action | Left mouse button |
| Change weapon | E |
| Ultimate | R |
| Jump | Space |
| Pause | P |

## Notes

- Course project, single player.
- No license: the source is shared to read and study; all rights reserved.

## Contact

Daniel Corredor — Senior Gameplay Engineer, Unreal Engine · [Portfolio](https://danielcorredorm.dev) · [LinkedIn](https://www.linkedin.com/in/danielcorredorm2787)
