## updated 2/6/2025 v0.0.3 :ramen: e_TimeOfDay=4.2

#### wip ultra config i will be optimizing more

#### mods ect under cfg

---

```python
## create user.cfg in kingdomcomedeliverance2 folder and copy paste
## delete cache folder %userprofile%/saved games/kingdomcome2/shaders (not needed, maybe after update)
## add launch commands: +exec user.cfg
## and restart after getting to main menu (needed depending on cvar)

sys_spec=0 ## "custom"
## sys_spec_full= ## "sets all"
## q_quality= ## "sets all"

## sys_spec_textureresolution=9 ## 9 "vram 7,8,9 8gb,12gb,16gb"
sys_spec_characters=4 ##
sys_spec_globalillumination=4 ##
sys_spec_light=4 ##
sys_spec_objectdetail=4 ##
sys_spec_particles=4 ##
sys_spec_postprocessing=4 ##
sys_spec_quality=4 ##
sys_spec_shading=4 ##
sys_spec_shadows=4 ##
sys_spec_texture=4 ##
sys_spec_vegetation=4 ##
sys_spec_volumetriceffects=4 ##

q_renderer=3 ##
q_shaderfx=3 ##
q_shadergeneral=3 ##
q_shaderglass=3 ##
q_shaderhdr=3 ##
q_shaderice=3 ##
q_shadermetal=3 ##
q_shaderpostprocess=3 ##
q_shadershadow=3 ##
q_shadersky=3 ##
q_shaderterrain=3 ##
q_shadervegetation=3 ##
q_shaderwater=3 ##

bind f2 "exec user.cfg" ## ""

cl_sensitivity=10 ## ""

r_multigpu=0 ## 1 ""
r_vsync=0 ## 1 ""
sys_maxfps=0 ## -1 ""

cl_fov=68 ## 63.0883 "68 is 100,59 is 90,horizontal"
pl_movement.power_sprint_targetfov=68 ## 55 "68 is 100,59 is 90,horizontal"
r_drawnearfov=68 ## 60 "68 is 100,59 is 90,horizontal"

r_superresolution_mode=2 ## "dlss"
r_superresolution_nvidia_dlss_qualitymode=1 ## "1,2,3 quality,balanced,performance"
r_superresolution_sharpness=0 ## 0.5 ""
r_superresolution_texturemipbias=0 ## 0 ""

g_radialblur=0 ## 1 "post process"
r_depthoffield=0 ## 2 "post process"
r_hdrgrainamount=0 ## 1 "post process"
r_hdrvignetting=0 ## 1 "post process"
r_motionblur=0 ## 2 "post process"

## r_texturesstreampoolsize=10240 ## 10240 "vram 5120,8192,10240 8gb,12gb,16gb"
ca_attachmentcullingration=1000 ## 1000 ""
e_coveragebufferterrainexpand=0.025 ## 0.025 ""
e_lodfaceareatargetsize=0.0012 ## 0.0012 ""
e_lodratio=60 ## 60 ""
e_mergedmeshesinstancedist=24 ## 24 ""
e_mergedmesheslodratio=30 ## 30 ""
e_mergedmeshesviewdistratio=140 ## 140 ""
e_physproxytrilimit=5000 ## 5000 ""
e_shadowscastviewdistratio=0.9 ## 0.9 ""
e_streamcgfpoolsize=1280 ## 1280 "ram"
e_svoti_lowspecmode=1 ## 1 ""
e_svoti_skycolormultiplier=0 ## 0 "overall lighting"
e_svoti_ssaoamount=0 ## 0 ""
e_svoti_voxelizeunderterrain=1 ## 1 "why is this 1"
e_terraindetailmaterialsviewdistz=80 ## 80 ""
e_tessellation=0 ## 0 "hw geometry tessellation why is it 0"
e_viewdistmin=5 ## 5 ""
e_viewdistratio=140 ## 140 ""
e_viewdistratiocustom=60 ## 60 ""
e_viewdistratiodetail=30 ## 30 ""
e_viewdistratiointeriorreflexlights=0.9 ## 0.9 ""
e_viewdistratiolights=24 ## 24 ""
e_viewdistratiovegetation=140 ## 140 ""
e_volumetricfog=1 ## 1 "volumetric fog"
es_maxphysdist=100 ## 100 ""
es_maxphysdistcloth=300 ## 300 ""
gpu_particle_physics=1 ## 0 "shouldn't this be 1"
log_enableremoteconsole=0 ## 1 ""
p_cull_distance=100 ## 100 ""
p_num_bodies_large_group=100 ## 100 "test 10"
p_num_threads=1 ## 1 "test 7"
r_colorbits=32 ## 32 ""
r_customresmaxsize=4096 ## 4096 ""
r_deferredshadingarealights=1 ## 1 ""
r_deferredshadingfiltergbuffer=0 ## 0 ""
r_deferredshadingsss=1 ## 1 ""
r_deferredshadingtiled=3 ## 3 ""
r_deferredshadingtiledhairquality=2 ## 2 ""
r_detaildistance=6 ## 6 ""
r_drawnearshadows=1 ## 1 ""
r_drawnearzrange=0.12 ## 0.12 ""
r_fogshadows=0 ## 0 ""
r_fogshadowswater=1 ## 1 ""
r_raindistmultiplier=2 ## 2 ""
r_rainmaxviewdist_deferred=150 ## 150 ""
r_rendertargetpoolsize=0 ## 0 "vram"
r_shadowspcfiltering=1 ## 1 ""
r_ssdoamountambient=2 ## 2 ""
r_ssdoamountreflection=4 ## 4 ""
r_ssdohalfres=2 ## 2 ""
r_ssdoradiusmin=0.015 ## 0.015 ""
r_ssreflections=2 ## 2 ""
r_ssreflhalfres=0 ## 0 ""
r_supersampling=0 ## 1 ""
r_texturesstreaming=2 ## 2 ""
r_texturesstreamingmaxrequestedmb=4 ## 4 "vram"
r_texturesstreampooldefragmentation=0 ## 0 ""
r_texturesstreampooldefragmentationmaxamount=524288 ## 524288 "vram"
r_texturesstreampooldefragmentationmaxmoves=8 ## 8 "vram"
r_volumetricfogtexdepth=64 ## 64 ""
r_waterreflectionsquality=0 ## 4 "4 is wrong should be 0"
sys_budget_streamingthroughput=1024 ## 1024 "ram"
sys_budget_sysmem=512 ## 512 "ram debug"
sys_budget_videomem=90 ## 90 "vram debug"
sys_flash_address_space=65536 ## 65536 "ram"
sys_flash_check_filemodtime=0 ## 0 ""
sys_limit_phys_thread_count=1 ## 1 "test 0"
sys_pakstreamcache=0 ## 0 "ram"
sys_physics_cpu=1 ## 1 "test 0"
sys_streaming_cpu=1 ## 1 ""
sys_streaming_cpu_worker=5 ## 5 "test 7"
sys_streaming_max_bandwidth=0 ## 0 "vram"
wh_env_raindiffusedarkening=0.4 ## 0.4 ""
wh_env_raindropsspeedbase=1.5 ## 1.5 ""

## e_particlesmotionblur=0 ## 0
## r_shadowscache=0 ## 0 ##
## r_shadowscacheresolutions= ##
## r_superresolution_amd_fsr_customresolutionscalewh=0.5 ## 0.5
## r_superresolution_amd_fsr_qualitymode=0 ## 0
## r_superresolution_sony_pssr_resolutionscale=0.5 ## 0.5
## r_xboximmediatethresholdpercent=5 ## 5
## wh_cs_playerlockdisabled=0 ## 0
## wh_pl_showfirecursor=0 ## 0
## wh_sys_nosavepotion=0 ## 0
## wh_ui_showcompass=1 ## 1
## wh_ui_showhud=1 ## 1
## wh_ui_showstats=1 ## 1
ca_clothblending=1 ## 1
ca_clothbypasssimulation=0 ## 0
ca_keepmodels=0 ## 0
ca_usedecals=0 ## 0
ca_usephysics=1 ## 1
e_brushes=1 ## 1
e_charlodmin=0 ## 0
e_clouds=1 ## 1
e_cullvegactivation=50 ## 50
e_decalslifetimescale=2 ## 2
e_decalsrange=20 ## 20
e_foliagewindactivationdist=25 ## 25
e_lodcompmaxsize=6 ## 6
e_lodfaceareatargetsizevegetationmult=1 ## 1
e_lodmax=5 ## 5
e_lodmin=0 ## 0
e_lodminttris=300 ## 300
e_maxviewdistspeclerp=1 ## 1
e_mergedmeshescullinglodratiowh=0.7 ## 0.7
e_mergedmeshesdissolverangewh=20 ## 20
e_mergedmeshesusedissolvewh=1 ## 1
e_objquality=4 ## 4
e_objshadowcastspec=4 ## 4
e_particlesgi=1 ## 1
e_particleslod=1 ## 1
e_particlesmaxscreenfill=180 ## 180
e_particlesmindrawpixels=1 ## 1
e_particlesobjectcollisions=2 ## 2
e_particlesquality=4 ## 4
e_particlesshadows=1 ## 1
e_particlessoftintersect=1 ## 1
e_particlessortquality=1 ## 1
e_shadows=1 ## 1
e_shadowsblendcascades=1 ## 1
e_shadowscastfadeoutratiolightswh=0.3 ## 0.3
e_shadowscastviewdistratiolights=0.1 ## 0.1
e_shadowsclouds=1 ## 1
e_shadowsmaxtexres=2048 ## 2048
e_shadowsmaxtexressunwh=2048 ## 2048
e_shadowsperobject=0 ## 0
e_shadowspoolsize=8192 ## 8192
e_shadowsresscale=2.8 ## 2.8
e_skybox=1 ## 1
e_skyquality=1 ## 1
e_sun=1 ## 1
e_svoti_conemaxlength=30 ## 30
e_svoti_diffuse_cache=0 ## 0
e_svoti_diffuseamplifier=0 ## 0
e_svoti_diffuseconewidth=8 ## 8
e_svoti_dualtracing=2 ## 2
e_svoti_emissivemultiplier=4 ## 4
e_svoti_gsmcascadelod=3 ## 3
e_svoti_integrationmode=0 ## 0
e_svoti_minvoxelopacity=0.01 ## 0.01
e_svoti_numberofbounces=2 ## 2
e_svoti_numstreamingthreads=2 ## 2
e_svoti_reflect_vox_max=500 ## 500
e_svoti_rsmconemaxlength=6 ## 6
e_svoti_saturation=0 ## 0
e_svoti_skipnongilights=0 ## 0
e_svoti_specularamplifier=0 ## 0
e_svoti_vegetationmaxopacity=1 ## 1
e_terraindetailmaterialsviewdistxy=35 ## 35
e_tessellationmaxdistance=30 ## 30
e_vegetationuseterraincolor=1 ## 1
e_vegetationuseterraincolordistance=250 ## 250
e_waterocean=0 ## 0
e_wateroceanfft=0 ## 0
e_waterwaves=0 ## 0
g_breakage_particles_limit=200 ## 200
i_mouse_accel=0 ## 0
i_mouse_smooth=0 ## 0
r_antialiasingmode=3 ## 3
r_antialiasingtaapattern=1 ## 1
r_antialiasingtaasharpening=0 ## 0
r_chromaticaberration=0 ## 0
r_colorgrading=1 ## 1
r_depthoffieldmode=1 ## 1
r_envcmresolution=2 ## 2
r_envtexresolution=3 ## 3
r_flarehqshafts=1 ## 1
r_flares=0 ## 0
r_flashdyntextureresquality=0 ## 0
r_hdrbloomquality=2 ## 2
r_hdreyeadaptationmode=1 ## 1
r_hdreyeadaptationspeed=3 ## 3
r_motionblurquality=2 ## 2
r_particleshalfres=0 ## 0
r_particlestessellation=1 ## 1
r_postprocesseffects=1 ## 1
r_postprocessfilters=1 ## 1
r_postprocessgamefx=1 ## 1
r_rain=2 ## 2
r_rainamount=1 ## 1
r_raindropseffect=1 ## 1
r_rainoccludersizetreshold=10 ## 10
r_refraction=1 ## 1
r_shadowcastinglightsmaxcount=24 ## 24
r_shadowsscreenspace=1 ## 1
r_sharpening=0 ## 0
r_snow=0 ## 0
r_ssdo=1 ## 1
r_ssdoamountdirect=0.7 ## 0.7
r_ssdocolorbleeding=0.8 ## 0.8
r_ssdoradius=0.1 ## 0.1
r_ssdoradiusmax=0.3 ## 0.3
r_ssdosecondarybandradius=15 ## 15
r_sunshafts=2 ## 2
r_supersamplingfilter=0 ## 0
r_texmaxanisotropy=16 ## 16
r_texminanisotropy=16 ## 16
r_texpreallocateatlases=0 ## 0
r_textureloddistanceratio=-1 ## -1
r_texturesstreamingminusablemips=8 ## 8
r_texturesstreamingskipmips=0 ## 0
r_volumetricclouds=2 ## 2
r_volumetricfogsample=2 ## 2
r_volumetricfogtexscale=10 ## 10
r_watercaustics=1 ## 1
r_watergodrays=1 ## 1
r_waterreflections=1 ## 1
r_watervolumecaustics=0 ## 0
s_occlusionmaxdistance=500 ## 500
wh_ai_lod_maxcountdetail=80 ## 80
wh_ai_lod_maxdetaildistance=180 ## 180
wh_ai_npcupdatebudgetlowerbound=3.5 ## 3.5
wh_ca_clothbudgetmaxframestoskip=1 ## 1
wh_ca_geometricmeanoverride=0.0004 ## 0.0004
wh_e_hlodclusterswitchingdistancemin=150 ## 150
wh_e_hlodclusterswitchingdistancemultiplier=0.5 ## 0.5
wh_e_hlodinteriorswitchingdistance=12 ## 12
wh_e_hlodvegetationswitchingdistances=8000 4000 2000 500 ## 8000 4000 2000 500
wh_e_particlesviewdistmul=3 ## 3
wh_e_svoti_useprobe=0 ## 0
wh_e_viewdistratioroad=130 ## 130
wh_env_dirtcreationspeed=0.05 ## 0.05
wh_env_dirtdryupspeed=0.05 ## 0.05
wh_env_puddlecreationdelay=25 ## 25
wh_env_puddlecreationspeed=0.017 ## 0.017
wh_env_puddledryupdelay=400 ## 400 
wh_env_puddledryupspeed=0.0008 ## 0.0008
wh_env_puddlemaskmin=0 ## 0
wh_env_raindropsamountmul=8 ## 8
wh_env_raindropsspeedmul=8 ## 8
wh_env_rainlayers=3 ## 3
wh_env_rainwindstrength=30 ## 30
wh_item_viewdistratio=100 ## 100
wh_pl_fowenabled=1 ## 1
wh_pl_fowvisibilityradius=100 ## 100
wh_player_deepwaterlevel=0.85 ## 0.85
wh_r_texturesstreamingscheduletimelimitus=3000 ## 3000
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
Combat Free Look - L Alt
Quick Chat With Focus - Mouse 3
Follow Npc Or Focus Camera - Mouse 3

Game Settings:
Telemetry - No
In-Game Chatter Subtitles - No

Mods:
Unlimited Saving Ii-14-1-0-1738700295.Zip
More Carry Weight - Ptf - Max-63-1-1-1738734672.7Z
```

---
