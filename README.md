# Why?
We were using Unity 2023 and very much impressed by how the new right click menu just need to type what we need
So we are trying to get it back, because Unity just scrap this menu on Unity 6 going forward (I'm not sure why, ask Unity)

Thanks to neon-age (https://github.com/neon-age/Unify) for pointing out how but I got annoying persistent error because the dll not using Nuget For Unity so in this module we will make it required that you install HarmonyX or Harmony from there too

Same as the original path from neon-age, this is just patch to bring back what's on Unity 2023 code and it's not a plugin to create new things, so when it broke.. well it broke and we need to push Unity to re-implement it or someone else to create it from scratch

# Requirement:
- Only use it for Unity 6000.0.17f or lower (anything higher have broken UI)
- Install NugetForUnity package: https://github.com/GlitchEnzo/NuGetForUnity
- Install Harmony or HarmonyX from NugetForUnity
  - we are using HarmonyX 2.10.2 since newest version on either Harmony and HarmonyX gives us errors 

# Installation:
- Open Unity Package Manager
- Click + icon and choose From Git URL
- copy paste Git URL of this repo
