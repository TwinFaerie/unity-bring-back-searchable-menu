# Why?
We were using Unity 2023 and very much impressed by how the new right click menu just need to type what we need
So we are trying to get it back, because Unity just scrap this menu on Unity 6 going forward (I'm not sure why, ask Unity)

Thanks to neon-age (https://github.com/neon-age/Unify) for pointing out how but I got annoying persistent error because the dll not using Nuget For Unity so in this module we will make it required that you install HarmonyX or Harmony from there too

# Requirement:
- Only tested for Unity 6 (specifically 6000.0.12f)
- Install NugetForUnity package: https://github.com/GlitchEnzo/NuGetForUnity
- Install Harmony or HarmonyX from NugetForUnity
  - we are using HarmonyX 2.10.2 since newest version on either Harmony and HarmonyX gives us errors 

# Installation:
- Open Unity Package Manager
- Click + icon and choose From Git URL
- copy paste Git URL of this repo
