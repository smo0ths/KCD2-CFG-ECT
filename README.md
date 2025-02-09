## updated 2/8/2025 v0.1.1c :ramen: e_timeofday=4.2

#### wip ultra config i will be optimizing more

#### mods ect under cfg

---

```python
## create user.cfg in kingdomcomedeliverance2 folder and copy paste
## delete cache folder %userprofile%/saved games/kingdomcome2/shaders (not needed, maybe after update)
## add launch commands: +exec user.cfg
## and restart after getting to main menu (needed depending on cvar)
## 🟩 shows changes from default ultra

## console access
con_restricted=0 #

## custom cfg
sys_spec=0 # 🟩

## sys cfg
sys_spec_characters=4 #
sys_spec_globalillumination=4 #
sys_spec_light=4 #
sys_spec_objectdetail=4 #
sys_spec_particles=4 #
sys_spec_postprocessing=4 #
sys_spec_quality=4 #
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

## custom sys 0
sys_budget_soundchannels=32 #32
sys_budget_soundcpu=15 #15 "test 0, monitoring budget"
sys_budget_streamingthroughput=1024 #1024 "test 3000, ram"
sys_budget_sysmem=512 #512 "test 0, ram, debug"
sys_budget_videomem=90 #90 "test 0, vram, debug"
sys_flash_address_space=65536 #65536 "test 131072, ram, require_app_restart"
sys_flash_check_filemodtime=0 #0
sys_maxfps=158 #-1 🟩
sys_pakstreamcache=0 #0 "test 1, ram"
sys_streaming_max_bandwidth=0 #0 "test 2000, vram"

## custom sys 1
sys_job_system_enable=1 #1
sys_job_system_max_worker=8 #16 "test 0,8" 🟩
sys_limit_phys_thread_count=1 #1 "limits p_num_threads to physical cpu count"
sys_main_cpu=0 #0 "game thread"
sys_physics_cpu=2 #1 "test 2" 🟩
sys_streaming_cpu=1 #1
sys_streaming_cpu_worker=5 #5
sys_taskthread0_cpu=3 #3
sys_taskthread1_cpu=5 #5
sys_taskthread2_cpu=4 #4
sys_taskthread3_cpu=3 #3
sys_taskthread4_cpu=2 #2
sys_taskthread5_cpu=1 #1

## custom 2
e_svoti_numstreamingthreads=2 #2 "test"
p_num_threads=1 #1 "test, internal physics threads"
r_waterupdatethread=5 #5

## custom 3
e_streamcgfpoolsize=1280 #1280 "test 512,1024,2048, ram, render mesh cache"
log_enableremoteconsole=0 #1 🟩
r_multigpu=0 #1 🟩
r_rendertargetpoolsize=0 #0 "test 1024, vram"
r_vsync=0 #1 🟩

## binds
bind mwheel_down cl_fov 68
bind mwheel_up cl_fov 25
bind slash exec root/user.cfg

## mouse
cl_sensitivity=10 # 🟩
i_mouse_accel=0 #0
i_mouse_smooth=0 #0

## sound volumes
s_mastervolume=1 #1
s_musicvolume=0.6 #1 🟩
s_soundvolume=1 #1

## field of views
cl_fov=68 #63.0883 "68 is 100, 59 is 90, horizontal" 🟩
pl_movement.power_sprint_targetfov=68 #55 "68 is 100, 59 is 90, horizontal" 🟩
r_drawnearfov=68 #60 "68 is 100, 59 is 90, horizontal" 🟩

## miscellaneous
ca_usephysics=1 #1 "physics simulation"
e_deformableobjects=1 #1 "deform physics"
e_mergedmeshesusespines=1 #1
e_skyquality=1 #1
e_statobjtessellationmode=1 #1 "pretessellated mesh"
e_tessellation=0 #0 "test 1, hw geometry tessellation"
e_vegetation=1 #1
r_colorbits=32 #32 "color resolution in bpp, require_app_restart"
r_refraction=1 #1
r_sunshafts=2 #2
r_usehwskinning=1 #1 "gpu deformation of a vertices"
r_usemateriallayers=2 #2 "material layers"
r_usezpass=2 #2 "expensive materials"
r_zfightingdepthscale=0.995 #0.995
r_zfightingextrude=0.001 #0.001
r_zpassdepthsorting=1 #1
r_zprepassmaxdist=16 #16
s_occlusionmaxdistance=500 #500
wh_pl_showfirecursor=1 #0 🟩
wh_ui_bubblesenabled=0 #0 🟩
wh_ui_enablesubtitlespeakername=1 #0 🟩
wh_ui_shownormalcursor=1 #1 🟩
wh_ui_subtitlesize=3 #0 🟩

## better antialiasing
r_superresolution_mode=2 # "dlss" 🟩
r_superresolution_nvidia_dlss_qualitymode=1 # "1,2,3, quality,balanced,performance" 🟩
r_superresolution_sharpness=0 #0.5 🟩
r_superresolution_texturemipbias=0 #0 "test 0.5,1"

## post process based antialiasing
r_antialiasingmode=3 #3
r_antialiasingtaapattern=1 #1
r_antialiasingtaasharpening=0 #0

## supersampled antialiasing
r_supersampling=0 #1 🟩
r_supersamplingfilter=0 #0

## post process
g_radialblur=0 #1 🟩
r_chromaticaberration=0 #0
r_colorgrading=1 #1
r_depthoffield=0 #2 🟩
r_depthoffieldbokehquality=0 #0
r_depthoffieldmode=1 #1
r_flarehqshafts=1 #1
r_flares=0 #0
r_hdrbloom=1 #1
r_hdrbloomquality=2 #2
r_hdreyeadaptationmode=1 #1
r_hdreyeadaptationspeed=3 #3
r_hdrgrainamount=0 #1 🟩
r_hdrrangeadapt=0 #0
r_hdrtexformat=1 #1
r_hdrvignetting=0 #1 🟩
r_motionblur=0 #2 "1,2, camera,camera and object" 🟩
r_motionblurquality=2 #2 "0,1,2, low,med,high, sample count"
r_motionblurshutterspeed=200 ##200
r_postprocesseffects=1 #1 "test 0,2, debug"
r_postprocessfilters=1 #1
r_postprocessgamefx=1 #1
r_sharpening=0 #0
r_ssreflections=2 #2
r_ssreflhalfres=0 #0
wh_cl_neardof=0 #0 🟩

## textures
r_envcmresolution=2 #2 "environment cubemap"
r_envtexresolution=3 #3 "2d target environment texture"
r_flashdyntextureresquality=0 #0
r_texmaxanisotropy=16 #16 "require_level_reload"
r_texminanisotropy=16 #16 "require_level_reload"
r_texpreallocateatlases=0 #0
r_textureloddistanceratio=-1 #-1
r_texturesstreaming=2 #2 "require_app_restart"
r_texturesstreamingmaxrequestedmb=4 #4 "test 20,1024, vram"
r_texturesstreamingminusablemips=8 #8
r_texturesstreamingskipmips=0 #0
r_texturesstreampooldefragmentation=0 #0 "test 1,2, vram"
r_texturesstreampooldefragmentationmaxamount=524288 #524288 "test 2097152,3145728, vram"
r_texturesstreampooldefragmentationmaxmoves=8 #8 "test 10,15, vram"
wh_r_texturesstreamingscheduletimelimitus=3000 #3000

## water
e_waterocean=0 #0
e_wateroceanbottom=1 #1
e_wateroceanfft=0 #0
e_watertessellationamount=10 #10
e_watertessellationamountx=10 #10 "test 85"
e_watertessellationamounty=10 #10 "test 85"
e_watertessellationswathwidth=12 #12 "test 10"
e_waterwaves=0 #0
e_waterwavestessellationamount=5 #5
r_watercaustics=1 #1 "test 0, not used"
r_watergodrays=1 #1 "test 0, not used"
r_waterreflections=1 #1 "test 0, not used"
r_waterreflectionsquality=4 #4 "test 0,1,2,3"
r_watervolumecaustics=0 #0
r_watervolumecausticsdensity=128 #128 "test 256"
r_watervolumecausticsmaxdist=35 #35

## fog
e_fog=1 #1 "render fog"
e_volumetricfog=1 #1 "volumetric fog, require_app_restart"
r_fogshadows=0 #0 "test 1"
r_fogshadowswater=1 #1 "test 0"
r_volumetricfogdownscaledsunshadow=-1 #-1 "test, volumetric fog sun shadows"
r_volumetricfogdownscaledsunshadowratio=1 #1
r_volumetricfogminimumlightbulbsize=2 #2 "test 0,0.4,1,2"
r_volumetricfogreprojectionblendfactor=0.9 #0.9
r_volumetricfogreprojectionmode=1 #1
r_volumetricfogsample=2 #2 "test 0,1"
r_volumetricfogshadow=1 #1 "test 0"
r_volumetricfogsunlightcorrection=1 #1
r_volumetricfogtexdepth=64 #64 "test 16,32"
r_volumetricfogtexscale=10 #10 "test 20"
wh_pl_fowenabled=1 #1
wh_pl_fowvisibilityradius=100 #100

## procedural volumetric clouds
r_volumetricclouds=2 #2 "test 0,1"
r_volumetriccloudspipeline=0 #0 "test 1"
r_volumetriccloudsraymarchstepnum=64 #64 "test 16 to 256"
r_volumetriccloudsshadowresolution=64 #64
r_volumetriccloudsstereoreprojection=1 #1
r_volumetriccloudstemporalreprojection=1 #1 "test 0"

## screen space directional occlusion
r_ssdo=1 #1
r_ssdoamountambient=2 #2 "test 1,1.5"
r_ssdoamountdirect=0.7 #0.7
r_ssdoamountreflection=4 #4 "test 5"
r_ssdocolorbleeding=0.8 #0.8
r_ssdohalfres=2 #2 "test 0,1,3"
r_ssdoradius=0.1 #0.1
r_ssdoradiusmax=0.3 #0.3
r_ssdoradiusmin=0.015 #0.015 "test 0.1,0.075"
r_ssdosecondarybandradius=15 #15

## voxel based global illumination
e_svoti_conemaxlength=30 #30
e_svoti_diffuse_cache=0 #0
e_svoti_diffuseamplifier=1 #1
e_svoti_diffuseconewidth=8 #8
e_svoti_dualtracing=2 #2
e_svoti_emissivemultiplier=4 #4
e_svoti_gsmcascadelod=3 #3
e_svoti_integrationmode=1 #1 "diffuse gi"
e_svoti_lowspecmode=1 #1 "test 2,3,4"
e_svoti_minvoxelopacity=0.01 #0.01
e_svoti_numberofbounces=2 #2
e_svoti_reflect_vox_max=500 #500
e_svoti_rsmconemaxlength=6 #6
e_svoti_saturation=1 #1
e_svoti_skipnongilights=0 #0
e_svoti_skycolormultiplier=-0.8001 #-0.8001 "test -0.2, overall lighting"
e_svoti_specularamplifier=1 #1
e_svoti_ssaoamount=1 #1 "test 1.5"
e_svoti_vegetationmaxopacity=1 #1
e_svoti_voxelizeunderterrain=1 #1 "test 0"
e_svovoxelpoolresolution=128 #128
e_svovoxgenres=512 #512
wh_e_svoti_useprobe=0 #0

## hierarchical level of detail
wh_e_hlodclusterswitchingdistancemin=150 #150
wh_e_hlodclusterswitchingdistancemultiplier=0.5 #0.5
wh_e_hlodinteriorswitchingdistance=12 #12
wh_e_hlodvegetationswitchingdistances=8000 4000 2000 500

## cloth
ca_clothblending=1 #1
ca_clothbypasssimulation=0 #0
ca_clothbypasssimulation=0 #0
ca_vclothmode=1 #1
es_maxphysdistcloth=300 #300 "test 100"
wh_ca_clothbudgetmaxframestoskip=1 #1

## particles
e_particles=1 #1
e_particlesgi=1 #1
e_particleslod=1 #1
e_particlesmaxscreenfill=180 #180
e_particlesmindrawpixels=1 #1
e_particlesobjectcollisions=2 #2
e_particlesquality=4 #4
e_particlesshadows=1 #1
e_particlessoftintersect=1 #1
e_particlessortquality=1 #1
g_breakage_particles_limit=200 #200 "test 160"
gpu_particle_physics=1 #0 "test 1, require_app_restart" 🟩
r_particleshalfres=0 #0
r_particlestessellation=1 #1
wh_e_particlesviewdistmul=3 #3

## shadows
e_gsmsizeswh=3,10,32,120,600
e_objshadowcastspec=4 #4
e_shadows=1 #1
e_shadowsadaptscale=2.72 #2.72
e_shadowsblendcascades=1 #1
e_shadowscastfadeoutratiolightswh=0.3 #0.3
e_shadowscastviewdistratio=0.9 #0.9 "test"
e_shadowscastviewdistratiolights=0.1 #0.1
e_shadowsclouds=1 #1
e_shadowsmaxtexres=2048 #2048
e_shadowsmaxtexressunwh=2048 #2048
e_shadowsperobject=0 #0
e_shadowspoolsize=8192 #8192
e_shadowsresscale=2.8 #2.8
r_drawnearshadows=1 #1
r_shadowcastinglightsmaxcount=24 #24
r_shadowspcfiltering=1 #1
r_shadowsscreenspace=1 #1

## deferred shading
r_deferredshading3pl=0 #3 "test, three point lighting" 🟩
r_deferredshadingarealights=1 #1
r_deferredshadingfiltergbuffer=0 #0
r_deferredshadingsss=1 #1
r_deferredshadingtiled=3 #3
r_deferredshadingtiledhairquality=2 #2

## lods 0
ca_attachmentcullingration=1000 #1000
ca_facialanimationradius=30 #30
e_lodcompmaxsize=6 #6 "test"
e_lodfaceareatargetsize=0.0012 #0.0012 "test 0.0006"
e_lodratio=60 #60 "test 70"
e_mergedmeshesinstancedist=24 #24 "test 16,32"
e_mergedmesheslodratio=30 #30 "test 16,8"
e_mergedmeshesviewdistratio=140 #140 "test 100"
e_streaminstancesminloadednodes=128 #128 "test 64"
e_terraindetailmaterialsviewdistz=80 #80 "test 100,120"
e_viewdistmin=5 #5 "test 10"
e_viewdistratio=140 #140 "test 125,150"
e_viewdistratiovegetation=140 #140 "test 65,100,125,150"
r_detaildistance=6 #6 "test 1 threw 20, perpixel detail layers blending"
wh_ai_lod_maxcountdetail=80 #80
wh_ai_lod_maxcountlod=400 #400
wh_ai_lod_maxdetaildistance=180 #180
wh_ca_geometricmeanoverride=0.0004 #0.0004
wh_e_viewdistratioroad=130 #130
wh_item_viewdistratio=100 #100

## lods 1
e_physproxytrilimit=5000 #5000 "test 1000"
es_maxphysdist=100 #100
g_tree_cut_reuse_dist=0 #0 "test 0.35"
p_cull_distance=100 #100
p_num_bodies_large_group=100 #100 "test 10"

## lods 2
e_charlodmin=0 #0
e_coveragebufferterrainexpand=0.025 #0.025 "axisaligned bounding box z to avoid flat terrain flickering"
e_cullvegactivation=50 #50
e_foliagewindactivationdist=25 #25
e_lodfaceareatargetsizevegetationmult=1 #1
e_lodmax=5 #5
e_lodmin=0 #0
e_lodminttris=300 #300
e_maxviewdistance=-1 #-1
e_maxviewdistspeclerp=1 #1
e_mergedmeshescullinglodratiowh=0.7 #0.7
e_mergedmeshesdissolverangewh=20 #20
e_mergedmeshesusedissolvewh=1 #1
e_objquality=4 #4 "test 3"
e_statobjmergemaxtrisperdrawcall=500 #500
e_terraindetailmaterialsviewdistxy=35 #35
e_tessellationmaxdistance=30 #30
e_vegetationuseterraincolor=1 #1
e_vegetationuseterraincolordistance=250 #250
e_viewdistratiointeriorreflexlights=0.9 #0.9
e_viewdistratiolights=24 #24
r_drawnearzrange=0.12 #0.12 "test"
wh_ai_npcupdatebudgetlowerbound=3.5 #3.5

## rain
r_rain=2 #2
r_rainamount=1 #1
r_raindistmultiplier=2 #2 "test 2.5"
r_raindropseffect=1 #1
r_rainmaxviewdist_deferred=150 #150 "test 170"
r_rainoccludersizetreshold=10 #10
wh_env_dirtcreationspeed=0.05 #0.05
wh_env_dirtdryupspeed=0.05 #0.05
wh_env_puddlecreationdelay=25 #25
wh_env_puddlecreationspeed=0.017 #0.017
wh_env_puddledryupdelay=400 #400 
wh_env_puddledryupspeed=0.0008 #0.0008
wh_env_puddlemaskmin=0 #0
wh_env_raindiffusedarkening=0.4 #0.4 "test 0.3"
wh_env_raindropsamountmul=8 #8
wh_env_raindropsspeedbase=1.5 #1.5 "test 3"
wh_env_raindropsspeedmul=8 #8
wh_env_rainlayers=3 #3
wh_env_rainwindstrength=30 #30

## decals
ca_usedecals=0 #0 "character decals"
e_decalsallowgamedecals=1 #1
e_decalsforcedeferred=0 #0
e_decalslifetimescale=2 #2
e_decalsoverlapping=1 #1
e_decalsplacementtestareasize=0.08 #0.08
e_decalsrange=20 #20

## etcetera, unused
#con_display_last_messages=0 #
#con_line_buffer_size=1000 #1000
#e_dynamiclights=1 #1
#e_particlesmotionblur= #
#e_viewdistratiocustom=60 #60 "not used"
#e_viewdistratiodetail=30 #30 "not used"
#memstats=0 #0 "debug"
#q_quality= # "sets all"
#q_shadersky= # "not used"
#r_displayinfo=0 #0 "debug"
#r_height=2160 #
#r_profiler=0 #0 "debug"
#r_shadowscache=0 #0
#r_shadowscacheresolutions= #
#r_superresolution_amd_fsr_customresolutionscalewh=0.5 #0.5
#r_superresolution_amd_fsr_qualitymode=0 #0
#r_superresolution_sony_pssr_resolutionscale=0.5 #0.5
#r_texturesstreampoolsize=10240 #10240 "vram 5120,8192,10240, 8gb,12gb,16gb"
#r_width=3840 #
#r_xboximmediatethresholdpercent=5 #5
#sys_pakpriority=2 #2 "test"
#sys_spec_full= # "sets all"
#sys_spec_textureresolution=9 #9 "vram 7,8,9, 8gb,12gb,16gb"
#wh_cs_playerlockdisabled=0 #0
#wh_player_deepwaterlevel=0.85 #0.85
#wh_sys_nosavepotion=0 #0
#wh_ui_showcompass=1 #1
#wh_ui_showhud=1 #1
#wh_ui_showstats=1 #1
```

---

## ect

```python
## enable rebar gives you ~3 fps (in nvidiaprofileinspector)

## update dlss to latest and force preset k(0x0000000B) (in nvidiaprofileinspector)

## keybinds
accept/use                  - v
combat free look            - l alt
cycle tabs                  - i
follow npc or focus camera  - mouse 3
inventory                   - tab
jump                        - space | mouse 4 (this is also dodge)
lock on opponent            - c
pat your dog or horse       - e
quick chat with focus       - mouse 3
special attack              - f | mouse 5 (kick in clinch/fistfight, mercy kill, tackle, stealth kill/takedown)
toggle crouch               - l ctrl

## game settings
in-game chatter subtitles - no
telemetry - no

## mods
more carry weight - ptf - max-63-1-1-1738734672.7z
unlimited saving ii-14-1-0-1738700295.zip
```

---
