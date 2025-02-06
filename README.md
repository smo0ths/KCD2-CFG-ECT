## updated 2/6/2025 v0.0.2 :ramen: e_TimeOfDay=4.2

#### wip ultra config i will be tweaking more later

#### mods ect under cfg

---

```python
## create user.cfg in kingdomcomedeliverance2 folder and copy paste
## delete cache folder %userprofile%/saved games/kingdomcome2/shaders (not needed, maybe after update)
## add launch commands: +exec user.cfg
## and restart after getting to main menu (needed depending on cvar)

Sys_Spec=4 ## "0 For Custom If You Change Sys_ Or Q_"

## Sys_Spec_Characters=4 ##
## Sys_Spec_Full= ## ""
## Sys_Spec_Globalillumination=4 ##
## Sys_Spec_Light=4 ##
## Sys_Spec_Objectdetail=4 ##
## Sys_Spec_Particles=4 ##
## Sys_Spec_Postprocessing=4 ##
## Sys_Spec_Quality= ## ""
## Sys_Spec_Shading=4 ##
## Sys_Spec_Shadows=4 ##
## Sys_Spec_Texture=4 ##
## Sys_Spec_Textureresolution=9 ## "7,8,9 8Gb,12Gb,16Gb Of Vram"
## Sys_Spec_Vegetation=4 ##
## Sys_Spec_Volumetriceffects=4 ##

## Q_Quality ##
## Q_Renderer=3 ##
## Q_Shaderfx=3 ##
## Q_Shadergeneral=3 ##
## Q_Shaderglass=3 ##
## Q_Shaderhdr=3 ## ""
## Q_Shaderice=3 ##
## Q_Shadermetal=3 ##
## Q_Shaderpostprocess=3 ## ""
## Q_Shadershadow=3 ##
## Q_Shadersky=3 ##
## Q_Shaderterrain=3 ##
## Q_Shadervegetation=3 ##
## Q_Shaderwater=3 ##

Bind F1 "Exec User.Cfg" ## ""
Bind F2 R_Reloadshaders 1 ## 0 ""
Cl_Fov=59 ## 63.0883 ""
Cl_Sensitivity=10 ## ""
Pl_Movement.Power_Sprint_Targetfov=59 ## 55 ""
R_Drawnearfov=59 ## 60 ""
Sys_Maxfps=0 ## -1 ""

## Wh_Cs_Playerlockdisabled=0 ## 0 ""
## Wh_Pl_Showfirecursor=0 ## 0 ""
## Wh_Sys_Nosavepotion=0 ## 0 ""
## Wh_Ui_Showcompass=1 ## 1 ""
## Wh_Ui_Showhud=1 ## 1 ""
## Wh_Ui_Showstats=1 ## 1 ""

## R_Texturesstreampoolsize=10240 ## "Vram"
E_Coveragebufferterrainexpand=0.025 ## 0.025 ""
E_Lodfaceareatargetsize=0.0012 ## 0.0012 ""
E_Lodratio=60 ## 60 ""
E_Mergedmeshesinstancedist=24 ## 24 ""
E_Mergedmesheslodratio=30 ## 30 ""
E_Mergedmeshesviewdistratio=140 ## 140 ""
E_Physproxytrilimit=5000 ## 5000 ""
E_Shadowscastviewdistratio=0.9 ## 0.9 ""
E_Streamcgfpoolsize=1280 ## 1280 "Ram"
E_Svoti_Lowspecmode=1 ## 1 ""
E_Svoti_Skycolormultiplier=0 ## 0 "Overall Lighting"
E_Svoti_Ssaoamount=0 ## 0 ""
E_Svoti_Voxelizeunderterrain=1 ## 1 "Why Is This 1"
E_Terraindetailmaterialsviewdistz=80 ## 80 ""
E_Tessellation=0 ## 0 "Hw Geometry Tessellation Why Is It 0"
E_Viewdistmin=5 ## 5 ""
E_Viewdistratio=140 ## 140 ""
E_Viewdistratiocustom=60 ## 60 ""
E_Viewdistratiodetail=30 ## 30 ""
E_Viewdistratiointeriorreflexlights=0.9 ## 0.9 ""
E_Viewdistratiolights=24 ## 24 ""
E_Viewdistratiovegetation=140 ## 140 ""
E_Volumetricfog=1 ## 1 "Volumetric Fog"
Es_Maxphysdist=100 ## 100 ""
Es_Maxphysdistcloth=300 ## 300 ""
G_Radialblur=0 ## 1 ""
Gpu_Particle_Physics=1 ## 0 "Shouldn'T This Be 1"
Log_Enableremoteconsole=0 ## 1 ""
P_Cull_Distance=100 ## 100 ""
P_Num_Bodies_Large_Group=100 ## 100 "Test 10"
P_Num_Threads=1 ## 1 "Test 7"
R_Colorbits=32 ## 32 ""
R_Customresmaxsize=4096 ## 4096 ""
R_Deferredshadingarealights=1 ## 1 ""
R_Deferredshadingfiltergbuffer=0 ## 0 ""
R_Deferredshadingsss=1 ## 1 ""
R_Deferredshadingtiled=3 ## 3 ""
R_Deferredshadingtiledhairquality=2 ## 2 ""
R_Depthoffield=0 ## 2 ""
R_Detaildistance=6 ## 6 ""
R_Drawnearshadows=1 ## 1 ""
R_Drawnearzrange=0.12 ## 0.12 ""
R_Fogshadows=0 ## 0 ""
R_Fogshadowswater=1 ## 1 ""
R_Hdrgrainamount=0 ## 1 ""
R_Hdrvignetting=1 ## 1 ""
R_Motionblur=0 ## 2 ""
R_Multigpu=0 ## 1 ""
R_Raindistmultiplier=2 ## 2 ""
R_Rainmaxviewdist_Deferred=150 ## 150 ""
R_Rendertargetpoolsize=0 ## 0 "Vram"
R_Shadowspcfiltering=1 ## 1 ""
R_Ssdoamountambient=2 ## 2 ""
R_Ssdoamountreflection=4 ## 4 ""
R_Ssdohalfres=2 ## 2 ""
R_Ssdoradiusmin=0.015 ## 0.015 ""
R_Ssreflections=2 ## 2 ""
R_Ssreflhalfres=0 ## 0 ""
R_Superresolution_Mode=2 ## "Dlss"
R_Superresolution_Nvidia_Dlss_Qualitymode=1 ## "1,2,3 Quality,Balanced,Performance"
R_Superresolution_Sharpness=0 ## 0.5 ""
R_Supersampling=0 ## 1 ""
R_Texturesstreaming=2 ## 2 ""
R_Texturesstreamingmaxrequestedmb=4 ## 4 "Vram"
R_Texturesstreampooldefragmentation=0 ## 0 ""
R_Texturesstreampooldefragmentationmaxamount=524288 ## 524288 "Vram"
R_Texturesstreampooldefragmentationmaxmoves=8 ## 8 "Vram"
R_Vsync=0 ## 1 ""
R_Waterreflectionsquality=0 ## 4 "4 Is Wrong Should Be 0"
Sys_Budget_Streamingthroughput=1024 ## 1024 "Ram"
Sys_Budget_Sysmem=512 ## 512 "Ram,Debug"
Sys_Budget_Videomem=90 ## 90 "Ram,Debug"
Sys_Flash_Address_Space=65536 ## 65536 "Ram"
Sys_Flash_Check_Filemodtime=0 ## 0 ""
Sys_Limit_Phys_Thread_Count=1 ## 1 "Test 0"
Sys_Pakstreamcache=0 ## 0 "Ram"
Sys_Physics_Cpu=1 ## 1 "Test 0"
Sys_Streaming_Cpu=1 ## 1 ""
Sys_Streaming_Cpu_Worker=5 ## 5 "Test 7"
Sys_Streaming_Max_Bandwidth=0 ## 0 "Vram"
Wh_Env_Raindiffusedarkening=0.4 ## 0.4 ""
Wh_Env_Raindropsspeedbase=1.5 ## 1.5 ""

## E_Particlesmotionblur=0 ## 0
## R_Shadowscache=0 ## 0 ##
## R_Shadowscacheresolutions= ##
## R_Superresolution_Amd_Fsr_Customresolutionscalewh=0.5 ## 0.5
## R_Superresolution_Amd_Fsr_Qualitymode=0 ## 0
## R_Superresolution_Sony_Pssr_Resolutionscale=0.5 ## 0.5
## R_Xboximmediatethresholdpercent=5 ## 5
Ca_Attachmentcullingration=1000 ## 1000
Ca_Clothblending=1 ## 1
Ca_Clothbypasssimulation=0 ## 0
Ca_Keepmodels=0 ## 0
Ca_Usedecals=0 ## 0
Ca_Usephysics=1 ## 1
E_Brushes=1 ## 1
E_Charlodmin=0 ## 0
E_Clouds=1 ## 1
E_Cullvegactivation=50 ## 50
E_Decalslifetimescale=2 ## 2
E_Decalsrange=20 ## 20
E_Foliagewindactivationdist=25 ## 25
E_Lodcompmaxsize=6 ## 6
E_Lodfaceareatargetsizevegetationmult=1 ## 1
E_Lodmax=5 ## 5
E_Lodmin=0 ## 0
E_Lodminttris=300 ## 300
E_Maxviewdistspeclerp=1 ## 1
E_Mergedmeshescullinglodratiowh=0.7 ## 0.7
E_Mergedmeshesdissolverangewh=20 ## 20
E_Mergedmeshesusedissolvewh=1 ## 1
E_Objquality=4 ## 4
E_Objshadowcastspec=4 ## 4
E_Particlesgi=1 ## 1
E_Particleslod=1 ## 1
E_Particlesmaxscreenfill=180 ## 180
E_Particlesmindrawpixels=1 ## 1
E_Particlesobjectcollisions=2 ## 2
E_Particlesquality=4 ## 4
E_Particlesshadows=1 ## 1
E_Particlessoftintersect=1 ## 1
E_Particlessortquality=1 ## 1
E_Shadows=1 ## 1
E_Shadowsblendcascades=1 ## 1
E_Shadowscastfadeoutratiolightswh=0.3 ## 0.3
E_Shadowscastviewdistratiolights=0.1 ## 0.1
E_Shadowsclouds=1 ## 1
E_Shadowsmaxtexres=2048 ## 2048
E_Shadowsmaxtexressunwh=2048 ## 2048
E_Shadowsperobject=0 ## 0
E_Shadowspoolsize=8192 ## 8192
E_Shadowsresscale=2.8 ## 2.8
E_Skybox=1 ## 1
E_Skyquality=1 ## 1
E_Sun=1 ## 1
E_Svoti_Conemaxlength=30 ## 30
E_Svoti_Diffuse_Cache=0 ## 0
E_Svoti_Diffuseamplifier=0 ## 0
E_Svoti_Diffuseconewidth=8 ## 8
E_Svoti_Dualtracing=2 ## 2
E_Svoti_Emissivemultiplier=4 ## 4
E_Svoti_Gsmcascadelod=3 ## 3
E_Svoti_Integrationmode=0 ## 0
E_Svoti_Minvoxelopacity=0.01 ## 0.01
E_Svoti_Numberofbounces=2 ## 2
E_Svoti_Numstreamingthreads=2 ## 2
E_Svoti_Reflect_Vox_Max=500 ## 500
E_Svoti_Rsmconemaxlength=6 ## 6
E_Svoti_Saturation=0 ## 0
E_Svoti_Skipnongilights=0 ## 0
E_Svoti_Specularamplifier=0 ## 0
E_Svoti_Vegetationmaxopacity=1 ## 1
E_Terraindetailmaterialsviewdistxy=35 ## 35
E_Tessellationmaxdistance=30 ## 30
E_Vegetationuseterraincolor=1 ## 1
E_Vegetationuseterraincolordistance=250 ## 250
E_Waterocean=0 ## 0
E_Wateroceanfft=0 ## 0
E_Waterwaves=0 ## 0
G_Breakage_Particles_Limit=200 ## 200
I_Mouse_Accel=0 ## 0
I_Mouse_Smooth=0 ## 0
R_Antialiasingmode=3 ## 3
R_Antialiasingtaapattern=1 ## 1
R_Antialiasingtaasharpening=0 ## 0
R_Chromaticaberration=0 ## 0
R_Colorgrading=1 ## 1
R_Depthoffieldmode=1 ## 1
R_Envcmresolution=2 ## 2
R_Envtexresolution=3 ## 3
R_Flarehqshafts=1 ## 1
R_Flares=0 ## 0
R_Flashdyntextureresquality=0 ## 0
R_Hdrbloomquality=2 ## 2
R_Hdreyeadaptationmode=1 ## 1
R_Hdreyeadaptationspeed=3 ## 3
R_Motionblurquality=2 ## 2
R_Particleshalfres=0 ## 0
R_Particlestessellation=1 ## 1
R_Postprocesseffects=1 ## 1
R_Postprocessfilters=1 ## 1
R_Postprocessgamefx=1 ## 1
R_Rain=2 ## 2
R_Rainamount=1 ## 1
R_Raindropseffect=1 ## 1
R_Rainoccludersizetreshold=10 ## 10
R_Refraction=1 ## 1
R_Shadowcastinglightsmaxcount=24 ## 24
R_Shadowsscreenspace=1 ## 1
R_Sharpening=0 ## 0
R_Snow=0 ## 0
R_Ssdo=1 ## 1
R_Ssdoamountdirect=0.7 ## 0.7
R_Ssdocolorbleeding=0.8 ## 0.8
R_Ssdoradius=0.1 ## 0.1
R_Ssdoradiusmax=0.3 ## 0.3
R_Ssdosecondarybandradius=15 ## 15
R_Sunshafts=2 ## 2
R_Superresolution_Texturemipbias=0 ## 0
R_Supersamplingfilter=0 ## 0
R_Texmaxanisotropy=16 ## 16
R_Texminanisotropy=16 ## 16
R_Texpreallocateatlases=0 ## 0
R_Textureloddistanceratio=-1 ## -1
R_Texturesstreamingminusablemips=8 ## 8
R_Texturesstreamingskipmips=0 ## 0
R_Volumetricclouds=2 ## 2
R_Volumetricfogsample=2 ## 2
R_Volumetricfogtexdepth=64 ## 64
R_Volumetricfogtexscale=10 ## 10
R_Watercaustics=1 ## 1
R_Watergodrays=1 ## 1
R_Waterreflections=1 ## 1
R_Watervolumecaustics=0 ## 0
S_Occlusionmaxdistance=500 ## 500
Wh_Ai_Lod_Maxcountdetail=80 ## 80
Wh_Ai_Lod_Maxdetaildistance=180 ## 180
Wh_Ai_Npcupdatebudgetlowerbound=3.5 ## 3.5
Wh_Ca_Clothbudgetmaxframestoskip=1 ## 1
Wh_Ca_Geometricmeanoverride=0.0004 ## 0.0004
Wh_E_Hlodclusterswitchingdistancemin=150 ## 150
Wh_E_Hlodclusterswitchingdistancemultiplier=0.5 ## 0.5
Wh_E_Hlodinteriorswitchingdistance=12 ## 12
Wh_E_Hlodvegetationswitchingdistances=8000 4000 2000 500 ## 8000 4000 2000 500
Wh_E_Particlesviewdistmul=3 ## 3
Wh_E_Svoti_Useprobe=0 ## 0
Wh_E_Viewdistratioroad=130 ## 130
Wh_Env_Dirtcreationspeed=0.05 ## 0.05
Wh_Env_Dirtdryupspeed=0.05 ## 0.05
Wh_Env_Puddlecreationdelay=25 ## 25
Wh_Env_Puddlecreationspeed=0.017 ## 0.017
Wh_Env_Puddledryupdelay=400 ## 400 
Wh_Env_Puddledryupspeed=0.0008 ## 0.0008
Wh_Env_Puddlemaskmin=0 ## 0
Wh_Env_Raindropsamountmul=8 ## 8
Wh_Env_Raindropsspeedmul=8 ## 8
Wh_Env_Rainlayers=3 ## 3
Wh_Env_Rainwindstrength=30 ## 30
Wh_Item_Viewdistratio=100 ## 100
Wh_Pl_Fowenabled=1 ## 1
Wh_Pl_Fowvisibilityradius=100 ## 100
Wh_Player_Deepwaterlevel=0.85 ## 0.85
Wh_R_Texturesstreamingscheduletimelimitus=3000 ## 3000
```

---

## ect

```python
Enable Rebar Gives You ~3 Fps (In Nvidiaprofileinspector)

Update Dlss To Latest And Force Preset K (In Nvidiaprofileinspector)

Keybinds:
Accept/Use - V
Pat Your Dog Or Horse - E
Toggle Crouch - L Ctrl
Lock On Opponent - C
Inventory - Tab
Cycle Tabs - I

Game Settings:
Telemetry - No
In-Game Chatter Subtitles - No

Mods:
Unlimited Saving II-14-1-0-1738700295.zip
More Carry Weight - PTF - MAX-63-1-1-1738734672.7z
```

---
