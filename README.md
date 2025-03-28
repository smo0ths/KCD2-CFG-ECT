## updated 3/28/2025 v0.3.5 :ramen: e_timeofday=4.2

#### ultra config

#### download open ALL MY MODS.zip and drop ALL MY MODS folder in your Mods folder (custom hud/f5 save(on horse to)/9969 weight)

#### check under config (how to/mods explained/ect)

---

```python
## create user.cfg in kingdomcomedeliverance2 folder and copy paste
## add launch command: +exec user.cfg (needed for binds to be read ect, -devmode not needed only for debug/dev tools)
## delete cache folder %userprofile%/saved games/kingdomcome2/shaders (not needed, maybe after update)
## and restart after getting to main menu (needed depending on cvar)
## type ?_superresolution or anything like ?_shadow or ?_texture in console ` key to find a cvar
## 🟩 shows changes from default ultra

## console access
con_restricted=0 #

## custom sys cfg
sys_spec=0 # 🟩

## sys cfg
sys_spec_characters=4 #
sys_spec_globalillumination=4 #
sys_spec_light=4 #
sys_spec_objectdetail=4 #
sys_spec_particles=4 #
sys_spec_postprocessing=4 #
sys_spec_shading=4 #
sys_spec_shadows=4 #
sys_spec_texture=4 #
sys_spec_vegetation=4 #
sys_spec_volumetriceffects=4 #

## shader quality
q_renderer=3 #
q_shaderfx=3 #
q_shadergeneral=3 #
q_shaderglass=3 #
q_shaderhdr=3 #
q_shaderice=3 #
q_shadermetal=3 #
q_shaderpostprocess=3 #
q_shadershadow=3 #
q_shaderterrain=3 #
q_shadervegetation=3 #
q_shaderwater=3 #

## misc
cl_hfov=100 #95 "100 horizontal" 🟩
cl_sensitivity=9 # 🟩
s_musicvolume=0.8 #1 🟩
sys_maxfps=-1 #-1 🟩

## binds
bind apostrophe exec root/test1.cfg #
bind comma r_sharpening 0 # "for cutscenes"
bind lbracket e_svoti_skycolormultiplier -0.8001 #-0.8001 "use at day"
bind mwheel_down cl_hfov 100 #
bind mwheel_up cl_hfov 45 #
bind rbracket e_svoti_skycolormultiplier 8.0001 #-0.8001 "use at night"
bind semicolon exec root/test2.cfg #
bind slash exec root/user.cfg #

## tweaks
r_3plkeydirstr=0,0,-90
#0,0,90 "comment breaks command" 🟩

## tweaks
cl_fovblendtime=0.25 #1 "test" 🟩
e_decalsallowgamedecals=1 #1 "test"
e_svoti_asynccompute=1 #0 "test 1, simultaneous compute" 🟩
e_svoti_reflect_vox_max=500 #500 "test 1"
e_viewdistmin=0 #5 🟩
e_viewdistratiodetail=0 #30 "test" 🟩
e_viewdistratiomodifiergamedecals=1 #4 🟩
e_viewdistratioportals=0 #60 "test" 🟩
e_wateroceanbottom=0 #1 🟩
es_maxphysdistcloth=180 #300 "test 80,100,180" 🟩
g_radialblur=0 #1 🟩
gpu_particle_physics=1 #0 "test 1, require_app_restart" 🟩
log_enableremoteconsole=0 #1 🟩
pl_movement.power_sprint_targetfov=67.6727 #55 "100 horizontal" 🟩
r_depthoffield=0 #2 🟩
r_detailtextures=1 #1 "test, texture overlays"
r_drawnearfov=67.6727 #60 "100 horizontal" 🟩
r_hdrgrainamount=0 #1 🟩
r_hdrrangeadapt=1 #0 "test" 🟩
r_hdrvignetting=0 #1 🟩
r_motionblur=0 #2 "1,2, camera,camera and object" 🟩
r_motionblurquality=0 #2 "0,1,2, low,med,high, sample count" 🟩
r_multigpu=0 #1 🟩
r_nohwgamma=1 #1 "test"
r_postprocesshud3d=1 #1 "test"
r_reflections=1 #1 "test"
r_reflectionsquality=3 #3 "test"
r_ssrefldistance=0.05 #0.15 "better ssr" 🟩
r_ssreflhalfres=1 #0  🟩
r_superresolution_mode=2 # "dlss" 🟩
r_superresolution_nvidia_dlss_preset=10 #0 "0,10 convolutional,transformer" 🟩
r_superresolution_sharpness=0 #0.5 🟩
r_supersampling=0 #1 🟩
r_thermalvision=0 #1 🟩
r_volumetricfogminimumlightbulbsize=2 #2 "interior lights fog"
r_volumetricfogtexdepth=32 #64 "test 16,32" 🟩
r_volumetricfogtexscale=12 #10 "test 12,20" 🟩
r_vsync=0 #1 🟩
r_watercaustics=1 #1
r_watergodrays=1 #1
r_waterreflections=1 #1 "test"
r_waterreflectionsquality=4 #4 "test, not documented"
sys_flash_edgeaa=0 #1 🟩
wh_ansel_enable=0 #1 🟩
wh_cl_neardof=0 #1 🟩
wh_cs_playerinputmousesensitivity=0.05 #0.1 "test" 🟩
wh_cs_playerinputmouseunlockmindistancetounlock=5 #15 "test" 🟩
wh_cs_playerinputmouseunlockmintime=0 #0.15 "test" 🟩
wh_cs_playerinputmouseunlockreturntime=0.15 #0.2 "test" 🟩
wh_e_particlesviewdistmul=2 #3 "test 2" 🟩
wh_horse_cameracentering=0 #0.2 "not a unknown command" 🟩
wh_pl_showfirecursor=1 #0 🟩
wh_snd_ignore_focus=1 #0 🟩
wh_ui_bubblesenabled=0 #1 🟩
wh_ui_enablesubtitlespeakername=1 #0 🟩
wh_ui_holdcursorduration=0.1 #0.3 🟩
wh_ui_showvignette=0 #1 🟩
wh_ui_subtitlesize=3 #0 🟩
```

---

## ect

```python
## enable rebar gives you ~3 fps (in nvidiaprofileinspector) (test, ymmv)

## update dlss to latest and force preset k(0x0000000B) (in nvidiaprofileinspector) (game presets to J which is older)

## seems to be a vrr bug just turn it off unless you need it or find a fix and want to use it

-------------------------------------------------------------

## keybinds
accept/use                  - v
combat free look            - l alt
cycle tabs                  - i
follow npc or focus camera  - mouse 3
inventory                   - tab
jump                        - space | mouse 4 (this is also dodge)
lock on opponent            - c
next opponent               - delete (just use c "lock on opponent")
pat your dog or horse       - e
previous opponent           - delete (just use c "lock on opponent")
quick chat with focus       - mouse 3
special attack              - f | mouse 5 (kick in clinch/fistfight, mercy kill, tackle, stealth kill/takedown)
toggle crouch               - l ctrl

-------------------------------------------------------------

## game settings
telemetry - no

-------------------------------------------------------------

## make mods
make folder Libs(or other files like Scripts) with your mod path after and edited file (e.g. "Libs\UI\Textures\hud.dds")
right click on Libs(or multiple files like Scripts) > winrar > archive > zip > rename Data.pak(not .zip) > on time tab uncheck high precision time format > press ok
e.g. KingdomComeDeliverance2\Mods\ALL MY MODS\Data\Data.pak\Libs\UI\Textures\hud.dds (should be the path)
extract then archive again if you want to edit files

-------------------------------------------------------------

## save mod
Mods\ALL MY MODS\Data\Data.pak\Libs\Config\defaultProfile.xml
(reference KingdomComeDeliverance2\Data\IPL_GameData.pak\Libs\Config\defaultProfile.xml)

add the <action consoleCmd="1" keyboard="f5" name="quicksave" onPress="1" />

  <!-- default -->
  <actionmap name="player" priority="default" exclusivity="0">
    <action consoleCmd="1" keyboard="f5" name="quicksave" onPress="1" />
    <include actionmap="movement" />
    <include actionmap="camera" />
    <include actionmap="interaction" />
    <include actionmap="draw_holster_torch" />
    <include actionmap="toggle_helmet" />
    <include actionmap="open_ui" />
    <action name="toggle_crouch" onPress="1" keyboard="_keybinds_ref_" xboxpad="xi_thumbr" pspad="pad_r3" />
    <action name="grab_body" onPress="1" onRelease="1" keyboard="_keybinds_ref_" xboxpad="xi_shoulderl" pspad="pad_l1" />
  </actionmap>

add the <action consoleCmd="1" keyboard="f5" name="quicksave" onPress="1" />

    <actionmap name="horse_mounted" priority="gameplay" exclusivity="1">
        <action consoleCmd="1" keyboard="f5" name="quicksave" onPress="1" />

Mods\ALL MY MODS\Data\Data.pak\Scripts\Startup\savefunc.lua
(reference KingdomComeDeliverance2\Data\Scripts.pak\Scripts\Startup\)

System.AddCCommand("quicksave", "quicksave()", "quicksaves")

function quicksave()
    if (Game.IsLoadingEngineSaveGame()) then
        return
    end

    Game.SaveGameViaResting()
end

-------------------------------------------------------------

## weight mod
Mods\ALL MY MODS\Data\Data.pak\Libs\Tables\rpg\rpg_param__Weight.xml
(reference KingdomComeDeliverance2\Data\Tables.pak\Libs\Tables\rpg\)

<?xml version="1.0" encoding="us-ascii"?>
<database xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" name="barbora" xsi:noNamespaceSchemaLocation="../database.xsd">
  <rpg_params version="1">
    <rpg_param rpg_param_key="BaseInventoryCapacity" rpg_param_value="9969" />
    <rpg_param rpg_param_key="MaxBaseInventoryCapacity" rpg_param_value="9969" />
  </rpg_params>
</database>

-------------------------------------------------------------

## for .dds files i used paint.net(from github) and save in this format
BC2 (Linear, DXT3)
Medium Compression
Error Metric - Uniform
Generate Mip Maps - Super Sampling
```

---
