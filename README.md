# Archive of Various ReShade Shaders
A set of effects used for [Reshade](https://reshade.me). 

Some of these shaders are from the [official reshade shader library](https://github.com/crosire/reshade-shaders), most of them just come from somewhere, whoever really knows where. 

### Prerequisites
You should have [Reshade](https://reshade.me) (preferably the latest) and reshade.fxh inside the `reshade-shaders\shaders` folder

### How to install
It's quite unorganized, I use the folder as a place to store any files I'd like to port into ReShade.
You should be able to find your Shader and Texture folders wherever you'd decided to install ReShade. 

Copy over all of the texture files to `reshade-shaders\textures`. Shaders to `reshade-shaders\shaders`.

I recommend to test out activating each shader individually for which ever program/game you intend to run. 

Some of these won't work in ReShade at all, some cause application crashes upon activation due to floating point errors.

### Effects included
The following effects are included: 
- 3DFX.fx
- ACES.fxh
- ASCII.fx
- AdaptiveFog.fx
- AdaptiveRim.fx
- AdaptiveSharpen.fx
- AdaptiveTonemapper.fx
- AmbientLight.fx
- ArcaneBloom.fx
- ArcaneBloom.fxh
- AreaCopy.fx
- ArtisticVignette.fx
- AspectRatio.fx
- AspectRatioSuite.fx
- BeforeAfter.fx
- Blending.fxh
- Bloom.fx
- BloomingHDR.fx
- BlueNoiseDither.fxh
- BlueNoiseMotionBlur.fx
- Border.fx
- BulgePinch.fx
- CRT.fx
- CRT_Lottes.fx
- CRT_Lottes.fxh
- CRT_Yee64.fx
- CRT_Yeetron.fx
- Cartoon.fx
- Checkerboard.fx
- CheckerboardInterlace.fx
- Chromakey.fx
- ChromaticAberration.fx
- CinematicDOF.fx
- Clarity.fx
- ColorAndDither.fxh
- ColorConversion.fxh
- ColorLab.fx
- ColorLab.fxh
- ColorMatrix.fx
- Colourfulness.fx
- ContrastSharpening.fx
- Cursor.fx
- CurvedMonitor.fx
- Curves.fx
- DLAA_Plus.fx
- DOF.fx
- DPX.fx
- Daltonize.fx
- Deband.fx
- Denoise.fx
- Depth3D.fx
- DepthAlpha.fx
- DepthHaze.fx
- Depth_Cues.fx
- DisplayDepth.fx
- Dither.fx
- DrawText.fxh
- Drunk.fx
- DynamicRaindrops.fx
- Emphasize.fx
- EyeAdaption.fx
- FXAA.fxh
- FakeHDR.fx
- FakeMotionBlur.fx
- FastSharp.fx
- FilmGrain.fx
- FilmGrain2.fx
- FilmicAnamorphSharpen.fx
- FilmicPass.fx
- FilmicSharpen.fx
- FineSharp.fx
- Flair.fx
- Flashlight.fx
- FlexibleCA.fx
- Flipbook.fx
- FocalDOF.fx
- FramerateLimiter.fx
- GaussianBlur.fx
- Glitch.fx
- GloomAO.fx
- HQ4X.fx
- HSLShift.fx
- HexLensFlare.fx
- HighPassSharpen.fx
- HoleFiller.fx
- Image.fx
- Interlaced.fx
- KeyCodes.fxh
- LUT.fx
- LUTTools.fx
- Layer.fx
- LensDistort.fx
- Letterbox.fx
- Levels.fx
- LevelsPlus.fx
- LiftGammaGain.fx
- LightDoF.fx
- LinearGammaWorkflow.fxh
- LiquidLens.fx
- LumaSharpen.fx
- MBMB.fx
- MXAO.fx
- Macros.fxh
- MagicBloom.fx
- MagicHDR.fx
- MinimalColorGrading.fx
- MonitorGamma.fx
- Monochrome.fx
- MultiFX.fx
- MultiLUT.fx
- NFAA.fx
- NGLamps- GGX.fxh
- NGLighting- Configs.fxh
- NGLighting- Shader.fxh
- NGLighting.fx
- NGLightingUI.fxh
- NeoBloom.fx
- NiceGuy_Lamps.fx
- NightVision.fx
- NormalMap.fx
- Nostalgia.fx
- Overlay.fx
- Overwatch.fxh
- PD80_00_Base_Effects.fxh
- PD80_00_Blend_Modes.fxh
- PD80_00_Color_Spaces.fxh
- PD80_00_Noise_Samplers.fxh
- PD80_01A_RT_Correct_Contrast.fx
- PD80_01B_RT_Correct_Color.fx
- PD80_01_Color_Gamut.fx
- PD80_02_Bloom.fx
- PD80_02_Bonus_LUT_pack.fx
- PD80_02_Cinetools_LUT.fx
- PD80_02_LUT_Creator.fx
- PD80_03_Color_Space_Curves.fx
- PD80_03_Curved_Levels.fx
- PD80_03_Filmic_Adaptation.fx
- PD80_03_Levels.fx
- PD80_03_Shadows_Midtones_Highlights.fx
- PD80_04_BlacknWhite.fx
- PD80_04_Color_Balance.fx
- PD80_04_Color_Gradients.fx
- PD80_04_Color_Isolation.fx
- PD80_04_Color_Temperature.fx
- PD80_04_Contrast_Brightness_Saturation.fx
- PD80_04_Magical_Rectangle.fx
- PD80_04_Saturation_Limit.fx
- PD80_04_Selective_Color.fx
- PD80_04_Selective_Color_v2.fx
- PD80_04_Technicolor.fx
- PD80_05_Sharpening.fx
- PD80_06_Chromatic_Aberration.fx
- PD80_06_Depth_Slicer.fx
- PD80_06_Film_Grain.fx
- PD80_06_Luma_Fade.fx
- PD80_06_Posterize_Pixelate.fx
- PD80_LUT_v2.fxh
- PPFX_Bloom.fx
- PPFX_Godrays.fx
- PPFX_SSDO.fx
- PerfectPerspective.fx
- PiecewiseFilmicTonemap.fx
- Pong.fx
- Prism.fx
- RadialSlitScan.fx
- RadiantGI.fx
- ReShade.fxh
- ReShadeUI.fxh
- ReflectiveBumpMapping.fx
- RetroFog.fx
- Rim.fx
- RimLight.fx
- SCurve.fx
- SMAA.fx
- SMAA.fxh
- Scatter.fx
- Sepia.fx
- SimpleGrain.fx
- Sketch.fx
- SlitScan.fx
- SlowSharp.fx
- Smart_Sharp.fx
- SplicedRadials.fx
- Splitscreen.fx
- StageDepth.fx
- SunsetFilter.fx
- SurfaceBlur.fx
- Swirl.fx
- Technicolor.fx
- Technicolor2.fx
- Temporal_AA.fx
- TiltShift.fx
- TinyPlanet.fx
- TrackingRays.fx
- Trails.fx
- TriDither.fx
- TriDither.fxh
- TripleMonitor.fx
- UIDetect.fx
- UIDetect.fxh
- UIMask.fx
- UnrealLens.fx
- Unsharp.fx
- Vectorscope.fx
- Vibrance.fx
- Vignette.fx
- VirtualResolution.fx
- VolumetricFogV2.0.fx
- VolumetricFog.fx
- Wave.fx
- Waveform.fx
- WhitepointFixer.fx
- ZebraLines.fx
- ZigZag.fx
- qUINT_bloom.fx
- qUINT_common.fxh
- qUINT_deband.fx
- qUINT_dof.fx
- qUINT_lightroom.fx
- qUINT_mxao.fx
- qUINT_sharp.fx
- qUINT_ssr.fx
