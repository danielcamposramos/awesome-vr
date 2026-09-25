# Awesome VR [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Virtual reality: the headsets, the runtimes that drive them, the standards that keep them portable, and the sixty years of attempts behind them.

Virtual reality is older than the personal computer. Morton Heilig built the Sensorama in 1962 and Ivan Sutherland hung a head-tracked display from a laboratory ceiling in 1968, and every headset since has been the same bargain: two images, two eyes, and a machine fast enough to redraw them when you move. What changed is the cull rate. Each wave of hardware brings a rush of platforms and then a wave of shutdowns, so this list names what was switched off as carefully as what ships, and prefers the open runtimes that keep a headset working after its store closes.

*AI was leveraged as a partner in the development of this work — [more information here](PROVENANCE.md).*

## Contents

- [History](#history)
- [Headsets](#headsets)
- [Tracking and rendering](#tracking-and-rendering)
- [Open standards and formats](#open-standards-and-formats)
- [Open source runtimes and Linux VR](#open-source-runtimes-and-linux-vr)
- [VR on 3D displays: the stereo spectator](#vr-on-3d-displays-the-stereo-spectator)
- [Engines and toolkits](#engines-and-toolkits)
- [Media formats](#media-formats)
- [Social platforms](#social-platforms)
- [Comfort, health and accessibility](#comfort-health-and-accessibility)
- [Enterprise and industrial VR](#enterprise-and-industrial-vr)
- [Platforms that were switched off](#platforms-that-were-switched-off)
- [Preservation](#preservation)
- [Communities and archives](#communities-and-archives)
- [In fiction](#in-fiction)
- [Related lists](#related-lists)
- [Known gaps](#known-gaps)

## History

### Precursors, 1960s–1980s

- [Sensorama](https://en.wikipedia.org/wiki/Sensorama) - Morton Heilig's 1962 machine, one of the earliest known examples of immersive multi-sensory technology: a stereoscopic display with stereo sound, fans, odour emitters and a motion chair, aimed at a single seated viewer.
- [Morton Heilig](https://en.wikipedia.org/wiki/Morton_Heilig) - The cinematographer who wanted to build the "cinema of the future", and who patented the Telesphere Mask, a head-mounted stereoscopic viewer with sound, in 1960, years before anyone had a computer to drive one.
- [The Sword of Damocles](https://en.wikipedia.org/wiki/The_Sword_of_Damocles_(virtual_reality)) - The 1968 head-mounted display built by Ivan Sutherland with Bob Sproull, Quintin Foster and Danny Cohen, and the first to redraw its image from the viewer's tracked head pose. It hung from the ceiling because it was too heavy to wear, and Sutherland described the leap plainly: "we didn't need a camera – we could substitute a computer".
- [Ivan Sutherland](https://en.wikipedia.org/wiki/Ivan_Sutherland) - The computer-graphics pioneer behind that display, and behind much of the vocabulary the field still uses.
- [Thomas A. Furness III](https://en.wikipedia.org/wiki/Thomas_A._Furness_III) - Built helmet-mounted displays for the US Air Force from 1966, led the Super Cockpit programme, and founded the University of Washington's Human Interface Technology Lab in 1989.
- [Videoplace](https://en.wikipedia.org/wiki/Videoplace) - Myron Krueger's mid-1970s "artificial reality" at the University of Connecticut, which put a participant's own video image inside a responsive graphic world without goggles or gloves.
- [Aspen Movie Map](https://en.wikipedia.org/wiki/Aspen_Movie_Map) - MIT's 1978 interactive drive through Aspen, filmed from a camera rig on a car: an ARPA-funded ancestor of virtual tourism and, decades later, of Street View.
- [Fakespace BOOM](http://www-cdr.stanford.edu/html/DesignSpace/sponsors/boom.html) - A stereo viewer on a counterbalanced tracking arm, sold from 1989 to customers including NASA; this is a contemporary 1994 description of the product line.
- [VPL Research](https://en.wikipedia.org/wiki/VPL_Research) - Founded in 1984, one of the first companies to develop and sell virtual reality products: the DataGlove, the EyePhone head-mounted display, the DataSuit and the RB2 system.
- [Jaron Lanier](https://en.wikipedia.org/wiki/Jaron_Lanier) - Co-founder of VPL with Thomas Zimmerman, and the person most responsible for the phrase "virtual reality" reaching the public.
- [Scott Fisher](https://en.wikipedia.org/wiki/Scott_Fisher_%28technologist%29) - Worked on VR at Atari's research lab before leading NASA Ames's VIEW project, the thread between the two.
- [Habitat](https://en.wikipedia.org/wiki/Habitat_%28video_game%29) - Lucasfilm's 1986 graphical virtual world for the Commodore 64, where "avatar" took on its modern meaning, a decade before consumer headsets returned.
- [Power Glove](https://en.wikipedia.org/wiki/Power_Glove) - Mattel's 1989 attempt to bring VPL's DataGlove to the Nintendo at $100: a commercial failure and the most widely owned VR-adjacent input device of its time.
- [Reflection Technology Private Eye](https://www.virtual-boy.com/images/972309/) - The scanned-LED eyepiece display developed from the mid-1980s and later licensed to Nintendo for the Virtual Boy, documented by the Planet Virtual Boy archive.
- [NASA VIEW](https://ntrs.nasa.gov/citations/19950007621) - The Virtual Environment Workstation at NASA Ames, where Scott Fisher, Michael McGreevy and Warren Robinett assembled a head-mounted display partly from a motorcycle helmet and drove it with the first dataglove used in VR. NASA's own technical report is the primary record.

### The 1990s wave

- [Cave automatic virtual environment](https://en.wikipedia.org/wiki/Cave_automatic_virtual_environment) - The CAVE, introduced in 1992 at the University of Illinois Chicago: projectors aimed at between three and six walls of a room-sized cube, the answer to headsets that put several people inside the same scene.
- [Virtuality Group](https://en.wikipedia.org/wiki/Virtuality_Group) - The British company that put VR in arcades from 1987, went bankrupt in 1997, and is the reason a generation met the medium standing in a ring with a visor on.
- [Sega VR](https://en.wikipedia.org/wiki/Sega_VR) - Announced in 1991 and cancelled in 1994. The stated reason is worth remembering: the effect was judged "too realistic", so players might move while wearing it and hurt themselves.
- [Forte VFX1](https://en.wikipedia.org/wiki/Forte_VFX1) - The 1995 consumer headset that actually shipped: helmet, handheld controller and an ISA card, with head tracking, stereoscopic 3D and stereo audio.
- [Brenda Laurel](https://en.wikipedia.org/wiki/Brenda_Laurel) - Co-founded Telepresence Research with Scott Fisher in 1990 and ran VR research at Interval Research from 1992, one of the field's few humanities-trained pioneers.
- [Sensics](https://en.wikipedia.org/wiki/Sensics) - Maker of panoramic professional headsets that tiled dozens of micro-displays (piSight, 2006), defunct since 2019.

### Japan, China and Korea

- [VR-1](https://en.wikipedia.org/wiki/VR-1) - Sega and Virtuality's motion-simulator attraction, opened in July 1994 at Yokohama Joypolis: head-tracked visors on a moving base.
- [Glasstron](https://en.wikipedia.org/wiki/Glasstron) - Sony's personal-viewing headsets from 1996, without positional tracking, sold as a portable large screen rather than as VR.
- [Olympus Eye-Trek FMD-200](https://www.olympus-global.com/en/news/2000a/nr000204fmd200e.html) - Olympus's February 2000 release for its second face-mounted display, after a 1998 first-class trial with Japan Airlines.
- [Gunpei Yokoi and Kenji Eno, 1996](https://shmuplations.com/yokoixeno/) - A translated interview in which the Virtual Boy's designer discusses building it, given shortly before his retirement.
- [AntVR](https://en.wikipedia.org/wiki/AntVR) - A crowdfunded 2014 headset, China's first widely covered answer to the Oculus Rift, later pivoting to AR.
- [Baofeng Mojing](https://www.uploadvr.com/baofeng-mojing-5-mobile-vr-china-leap-motion/) - Once China's best-selling phone-VR viewer line, sold for a few dollars; the company is now defunct.
- [Xiaomi Mi VR Play](https://www.gsmarena.com/xiaomi_launches_mi_vr_play_headset_in_india-news-22121.php) - Xiaomi's 2016 fabric-and-lens viewer in the Cardboard mould, at about $15.
- [Alibaba Buy+](https://www.scmp.com/business/article/2044862/tmalls-cat-vr-may-bolster-alibabas-2016-singles-day-haul-29-cent-analysts) - A VR shopping demonstration for Singles' Day 2016, not continued.
- [HTC Vive Wave](https://www.vive.com/us/newsroom/2017-11-14/) - HTC's November 2017 open mobile-VR platform, whose launch release names a dozen Chinese partners (Baofeng, Coocaa, iQIYI, Pico and more): a snapshot of a fragmented market.
- [ByteDance acquires Pico](https://roadtovr.com/bytedance-tiktok-acquire-pico-report/) - The August 2021 purchase that turned a mid-tier Chinese headset maker into the platform behind the Pico 4.
- [LG 360 VR](https://www.androidpolice.com/2016/02/21/hands-on-with-the-lg-360-vr-headset/) - LG's 2016 phone-tethered headset with its own displays, launched with the G5; discontinued.
- [Samsung Odyssey](https://vrarwiki.com/wiki/Samsung_Odyssey) - Samsung's 2017 Windows Mixed Reality headset, left behind when the platform was deprecated (see below).

### The consumer revival

- [Oculus Rift](https://en.wikipedia.org/wiki/Oculus_Rift) - The 2012 development kit that restarted the category and set the shape of everything in the next section.

## Headsets

- [Meta Quest](https://en.wikipedia.org/wiki/Meta_Quest) - The standalone line that made headsets a mass product, and the largest headset platform in the world as of 2025. The Quest, Quest 2 and Quest Pro are already discontinued, which is the pattern this list keeps pointing at.
- [Meta Quest 3S](https://en.wikipedia.org/wiki/Meta_Quest_3S) - The entry-level sibling, unveiled on 25 September 2024: the Quest 3's Snapdragon XR2 Gen 2 and colour passthrough, with Fresnel lenses instead of pancake lenses.
- [Samsung Galaxy XR](https://en.wikipedia.org/wiki/Samsung_Galaxy_XR) - Samsung's mixed-reality headset, made with Google and Qualcomm and unveiled on 21 October 2025 at US$1,799: the first device to run [Android XR](https://en.wikipedia.org/wiki/Android_XR).
- [Meta Quest 3](https://en.wikipedia.org/wiki/Meta_Quest_3) - Released in October 2023 on a Snapdragon XR2 Gen 2, with colour passthrough that made mixed reality ordinary on a consumer headset.
- [PlayStation VR2](https://en.wikipedia.org/wiki/PlayStation_VR2) - Sony's 2023 headset: dual OLED panels at 2000×2040 per eye, 110° field of view, and eye tracking used for foveated rendering rather than only for input.
- [Apple Vision Pro](https://en.wikipedia.org/wiki/Apple_Vision_Pro) - Released in February 2024 at roughly 3660×3200 per eye, driven by an M-series chip paired with a dedicated R1 for sensor fusion, and unlocked by iris recognition.
- [Steam Frame](https://en.wikipedia.org/wiki/Steam_Frame) - Valve's standalone headset, announced in November 2025 and launched on 14 September 2026. Unlike the Index it needs no base stations, tracking itself from onboard cameras.
- [Valve Index](https://en.wikipedia.org/wiki/Valve_Index) - The 2019 PC headset built around Lighthouse base stations and the finger-tracking Knuckles controllers, discontinued in November 2025. Read it against the Steam Frame above: that pair is the whole industry's move from external tracking to onboard.
- [HTC Vive](https://en.wikipedia.org/wiki/HTC_Vive) - The 2016 headset, built with Valve, that introduced room-scale tracking to consumers: photosensors on the headset and controllers timed against laser sweeps from base stations in the corners of the room.
- [Bigscreen Beyond](https://en.wikipedia.org/wiki/Bigscreen_Beyond) - A 127-gram tethered headset whose face gasket is 3D-printed from a scan of the buyer's own face, discontinued in March 2025 in favour of a second version.
- [Varjo](https://en.wikipedia.org/wiki/Varjo) - The Finnish maker of high-resolution headsets for simulation and industry, founded in 2016 by former Nokia and Microsoft engineers, at clarity well beyond consumer hardware.
- [Pimax](https://en.wikipedia.org/wiki/Pimax) - The Shanghai maker that chased field of view first, shipping very wide, high-resolution PC headsets since its 2017 crowdfunding campaign.

### China and Japan

- [PICO](https://www.picoxr.com/global) - Standalone headset maker founded in 2015 and owned by ByteDance since 2021.
- [DPVR](https://www.dpvr.com/en/about-us/) - Shanghai maker of consumer and enterprise headsets, selling since 2015.
- [NOLO](https://www.nolovr.com/En/Culture) - Beijing company behind early six-degree-of-freedom tracking kits for phone VR, now also making headsets.
- [iQIYI QIYU 3](https://www.prnewswire.com/news-releases/iqiyi-launches-new-all-in-one-vr-headset-qiyu-3-further-expanding-its-premium-vr-gaming-ecosystem-301366852.html) - The streaming company's third standalone headset, with its own inside-out tracking.
- [Huawei VR Glass](https://en.wikipedia.org/wiki/Huawei_VR_Glass) - A slim tethered viewer from December 2019, later updated with six-degree-of-freedom tracking.
- [Skyworth VR V901](https://skarredghost.com/2019/11/09/skyworth-vr-v901-review/) - A 4K three-degree-of-freedom standalone headset from the Shenzhen electronics group, reviewed in depth.
- [3Glasses](https://web.archive.org/web/20180104060201/http://www.3glasses.com:80/en/aboutUs.html) - Maker of China's first VR headset (D1) and first Windows Mixed Reality headset (Blubur S1), archived from its 2018 site, which no longer answers; Digital Domain [bought 60% of it](https://digitaldomain.com/news/%E3%80%90media-alert%E3%80%91digital-domain-announces-acquisition-3glasses-virtual-reality-headset-manufacturer/) that year.
- [FOVE](https://fove-inc.com/) - Tokyo maker of the first consumer eye-tracking VR headset, [crowdfunded](https://www.kickstarter.com/projects/fove/fove-the-worlds-first-eye-tracking-virtual-reality) in 2015 and shipping from 2017.
- [Shiftall MeganeX](https://en.shiftall.net/our-products) - Ultra-light OLED PC headsets from a Panasonic spin-off, which Shiftall now runs alone.
- [Canon MREAL](https://global.canon/en/technology/canon-tech/tech/mr/) - Canon's mixed-reality headsets for industry and design.

## Tracking and rendering

- [Positional tracking](https://en.wikipedia.org/wiki/Positional_tracking) - How a headset knows where it is. Outside-in tracking watches the headset from fixed sensors in the room; inside-out puts the cameras on the headset and has it look outward, which is why current hardware ships without base stations.
- [Eye tracking](https://en.wikipedia.org/wiki/Eye_tracking) - In headsets it is an input and a budget: knowing where the eye is looking lets the renderer spend its pixels there.
- [Foveated rendering](https://en.wikipedia.org/wiki/Foveated_rendering) - The technique that follows from it, rendering at full detail only where the eye is pointed. Combined with sparse rendering and learned reconstruction it can cut the pixels actually drawn by an order of magnitude.

## Open standards and formats

The editions, registries and reference implementations are indexed in [standards.md](standards.md).

- [OpenXR](https://en.wikipedia.org/wiki/OpenXR) - The Khronos standard, released as 1.0 in July 2019, that replaced one vendor API per headset. Everything in the next section depends on it.
- [OpenVR](https://en.wikipedia.org/wiki/OpenVR) - Valve's SDK and API, public since April 2015 and the default runtime interface for SteamVR, which is why so many existing games speak it rather than OpenXR.
- [WebXR](https://en.wikipedia.org/wiki/WebXR) - Stereo rendering and tracking in the browser, maintained by the W3C Immersive Web groups as the successor to WebVR.
- [WebXR Device API](https://www.w3.org/TR/webxr/) - The specification itself, for when the question is what a runtime is actually required to do.
- [Khronos Group](https://en.wikipedia.org/wiki/Khronos_Group) - The consortium of over 180 member companies behind OpenXR, glTF and Vulkan, and the reason those standards are royalty-free.
- [glTF](https://en.wikipedia.org/wiki/GlTF) - The Khronos transmission format that most XR content pipelines settle on.
- [OpenXR 1.0 announcement](https://www.khronos.org/news/press/khronos-releases-openxr-1.0-specification-establishing-a-foundation-for-the-ar-and-vr-ecosystem) - Khronos's July 2019 release of the standard.
- [OpenXR-SDK-Source](https://github.com/KhronosGroup/OpenXR-SDK-Source) - The reference OpenXR loader and API layers: the code that finds and loads a runtime such as Monado or SteamVR.
- [OpenVR source](https://github.com/ValveSoftware/openvr) - Valve's own repository for the SDK and API.
- [WebXR Hand Input Module](https://www.w3.org/TR/webxr-hand-input-1/) - Articulated hand tracking for WebXR, with explicit consent written into the specification.
- [Immersive Web proposals](https://github.com/immersive-web/proposals) - Where new WebXR features are argued before they become modules.
- [glTF at Khronos](https://www.khronos.org/gltf/) - The format's own home, with the [extensions registry](https://github.com/KhronosGroup/glTF/tree/main/extensions) a real pipeline has to track.
- [KTX 2.0](https://www.khronos.org/ktx/) - Khronos's texture container with Basis Universal supercompression, for fitting texture-heavy scenes into a standalone headset.
- [Vulkan](https://www.khronos.org/vulkan/) - The cross-platform GPU API that a growing share of XR engines render through.
- [VRML](https://en.wikipedia.org/wiki/VRML) - The 1994 web 3D format, the ancestor in the line that runs through [COLLADA](https://en.wikipedia.org/wiki/COLLADA) and [X3D](https://www.web3d.org/x3d/what-x3d) to glTF.
- [Web3D Consortium](https://en.wikipedia.org/wiki/Web3D_Consortium) - The non-profit behind X3D, a royalty-free ISO standard.
- [VRPN](https://github.com/vrpn/vrpn) - The device-independent, network-transparent library for VR peripherals, from UNC in the 1990s and still maintained.
- [OSVR](https://github.com/OSVR) - Razer and Sensics's open platform; its osvr.org domain no longer resolves, so the code on GitHub is what remains.
- [ISO/IEC 23090-2 (OMAF)](https://www.iso.org/standard/73310.html) - The omnidirectional media format, MPEG-I part 2, for 360° video.
- [MPEG-I](https://www.mpeg.org/standards/MPEG-I/) - ISO/IEC 23090, the immersive-media family: omnidirectional video (OMAF), immersive audio and volumetric video.
- [ISO/IEC JTC 1/SC 24](https://en.wikipedia.org/wiki/ISO/IEC_JTC_1/SC_24) - The subcommittee for computer graphics, VR, AR and mixed reality, with its [ISO committee page](https://www.iso.org/committee/45252.html).
- [IEEE VR/AR Advisory Board](https://standards.ieee.org/industry-connections/activities/vr-ar-advisory-board/) - The IEEE Standards Association's umbrella for its VR and AR work, including [IEEE 2048.101](https://standards.ieee.org/ieee/2048.101/10390/), the one part of the 2048 family confirmed active.
- [W3C Immersive Web](https://www.w3.org/immersive-web/) - The W3C groups that own WebXR.
- [Metaverse Standards Forum](https://metaverse-standards.org/) - A coordination forum for XR and 3D standards; it publishes none of its own.
- [VRM](https://vrm.dev/en/) - A humanoid avatar format built as a glTF profile, maintained by the VRM Consortium, so an avatar can move between social platforms instead of belonging to one.

## Open source runtimes and Linux VR

- [Monado](https://monado.dev) - The cross-platform open-source OpenXR runtime for Linux, Windows and Android, developed at Collabora, and the foundation most of the rest of this section builds on.
- [OpenHMD](https://github.com/OpenHMD/OpenHMD) - The earlier free driver library covering a wide range of headsets. Its own readme now points users to Monado for active development, which is the honest way to read it: historically important, no longer where the work happens.
- [ALVR](https://github.com/alvr-org/ALVR) - Streams PC VR to a standalone headset over Wi-Fi, and one of the most actively developed projects in this list.
- [WiVRn](https://github.com/WiVRn/WiVRn) - The same idea built on Monado and aimed at Linux hosts, streaming a PC's VR output to a standalone headset.
- [Envision](https://gitlab.com/gabmus/envision) - A graphical front end that builds and runs a whole Monado and WiVRn stack for you, which is the practical answer to "how do I get VR working on Linux at all".
- [OpenComposite](https://gitlab.com/znixian/OpenOVR) - Translates OpenVR calls into OpenXR, so games written for SteamVR can run on another runtime entirely.
- [xrdesktop](https://gitlab.freedesktop.org/xrdesktop/xrdesktop) - Collabora's project, sponsored by Valve, for using ordinary desktop environments such as GNOME and KDE inside a headset.
- [Stardust XR](https://github.com/StardustXR/server) - A display server for VR and AR headsets on Linux, rather than a runtime that hosts one application at a time.
- [libsurvive](https://github.com/collabora/libsurvive) - An MIT-licensed reimplementation of Lighthouse tracking, so Vive-era trackers work without any proprietary runtime.
- [SlimeVR](https://slimevr.dev/) - Open hardware and software for full-body tracking with inexpensive IMU trackers and no base stations.
- [Linux VR Adventures](https://vronlinux.org/) - The community wiki collecting the guides, hardware notes and workarounds that make the above usable.

## VR on 3D displays: the stereo spectator

Every VR game already renders two eyes. The 3D televisions, projectors and monitors people still own want exactly that: two eye images, packed side by side or top and bottom, watched with the display's own glasses. What stands in between is everything a VR mode does *for a headset*: head tracking, lens distortion, a HUD floating as a panel in space, a cursor inside a virtual screen. The stereo spectator, designed by Daniel Campos Ramos in 2026, removes those and keeps the two eyes: someone plays in the headset while the room watches in depth on the television (spectator), or there is no headset at all and the display is the only screen (player).

- [VR Stereo Spectator](https://github.com/danielcamposramos/sony-bravia-linux/tree/main/tools/vr-stereo-spectator) - The first working case, September 2026: a replacement `sourcevr.so` that implements Half-Life 2's own VR interface for a 3D television instead of a headset, on Linux with Vulkan and an NVIDIA card, played on two Sony 3D sets. Off-axis eyes sharing one window at the screen plane, the game's view in place of head tracking, the HUD and crosshair as a 2D layer at zero parallax, menus in the game's own layout, the pointer confined to what the eyes show. A full playthrough section ran clean across saves and level transitions. Source 1 SDK License, with a provenance file.
- [The formula](https://github.com/danielcamposramos/sony-bravia-linux/blob/main/tools/vr-stereo-spectator/FORMULA.md) - What any VR engine has to change to drive a 3D display instead of a headset, learned on Half-Life 2 and written game-neutral: eyes, view, composition, the 2D layer, crosshair, weapon effects, input, settings. Shadows, lighting, level transitions and saves needed nothing, because the engine renders each eye itself; that is the advantage over a stereo proxy for games without a VR mode, which is what [wiz3D](https://github.com/effcol/wiz3D) does.
- [Anaglyph for any colour screen](https://github.com/danielcamposramos/sony-bravia-linux/tree/main/tools/vr-stereo-spectator/anaglyph) - The fallback for screens with no 3D mode: a [gamescope](https://github.com/ValveSoftware/gamescope) effect, 64-bit and outside the game, that turns the side-by-side output into red/cyan anaglyph with a matrix computed for CRT phosphors or one computed for modern LCD panels. It works for any game that outputs side by side; an artefact in fast camera turns is still under investigation.
- [Source-1-Games #8297](https://github.com/ValveSoftware/Source-1-Games/issues/8297) - The report to Valve: six behaviours of Half-Life 2's VR mode that only hurt a display, and one ask, to allow `viewmodel_fov` while VR mode is active. Filed on 24 September 2026, together with answers to the 2013 request for side-by-side 3D ([#1013](https://github.com/ValveSoftware/Source-1-Games/issues/1013)), the unanswered 2022 question about sourcevr on Linux ([#3782](https://github.com/ValveSoftware/Source-1-Games/issues/3782)) and the 2014 HUD checkerboard ([source-sdk-2013 #268](https://github.com/ValveSoftware/source-sdk-2013/issues/268)), whose cause turned out to be a material drawn without a precache.
- [SteamVR-for-Linux #961](https://github.com/ValveSoftware/SteamVR-for-Linux/issues/961) - The runtime-level ask, the same day: a side-by-side option for SteamVR's VR View mirror window, and a supported path for an OpenVR driver that presents a 3D display as the headset, the route [openvr #706](https://github.com/ValveSoftware/openvr/issues/706) tried in 2018. Valve had already said stereoscopic content on the [Steam Frame](https://roadtovr.com/valve-steam-frame-stereoscopic-3d-support-flat-games-spatial-video/) is "on our list"; a stereo spectator output is that side-by-side frame going the other way.
- [Awesome Stereoscopy](https://github.com/danielcamposramos/awesome-stereoscopy) - The companion list: the displays these eye images can go to, from the 2010 television wave to the glasses-free light-field sets shown in 2026.

## Engines and toolkits

- [Godot XR](https://docs.godotengine.org/en/stable/tutorials/xr/index.html) - The engine's own XR documentation, covering OpenXR setup, action maps and hand and body tracking, in a fully free engine.
- [StereoKit](https://stereokit.net/) - A C# and C++ framework that targets any OpenXR runtime, from Quest and HoloLens 2 to Monado on Linux, and prioritises XR application development over general engine features.
- [Unity XR Interaction Toolkit](https://docs.unity3d.com/Packages/com.unity.xr.interaction.toolkit@3.6/manual/index.html) - Unity's component-based interaction system for building VR and AR experiences.
- [Unreal Engine OpenXR](https://dev.epicgames.com/documentation/en-us/unreal-engine/developing-for-head-mounted-experiences-with-openxr-in-unreal-engine) - Epic's documentation for head-mounted development against OpenXR rather than per-vendor plugins.

## Media formats

- [360-degree video](https://en.wikipedia.org/wiki/360-degree_video) - A recording of every direction at once, shot with an omnidirectional camera or a rig. Worth being precise about: the viewpoint is fixed and the scene is not interactive, so it is watched in a headset without being virtual reality in the full sense.
- [Volumetric video](https://en.wikipedia.org/wiki/Volumetric_video) - Captured scenes a viewer can move through with six degrees of freedom, which is what 360° video is not.
- [Ambisonics](https://en.wikipedia.org/wiki/Ambisonics) - Full-sphere, speaker-independent sound. Its scene can be rotated to match the viewer's head and then decoded to binaural stereo, which is what makes audio hold still while the world turns.
- [AmbiX](https://ambisonics.iem.at/proceedings-of-the-ambisonics-symposium-2011/ambix-a-suggested-ambisonics-format) - The 2011 IEM Graz paper defining the channel order and normalisation most VR spatial-audio tools now assume.

## Social platforms

- [VRChat](https://en.wikipedia.org/wiki/VRChat) - The 2014 platform where users meet as their own 3D avatars in worlds other users built, and still the centre of gravity for social VR.
- [Resonite](https://en.wikipedia.org/wiki/Resonite) - Released in October 2023 as the successor to NeosVR, after its creator left that project in a dispute over cryptocurrency features. Its design principle is that virtually all content can be remixed and edited in real time, inside the session.
- [Second Life](https://en.wikipedia.org/wiki/Second_Life) - Linden Lab's 2003 desktop virtual world, the social-avatar ancestor of the platforms above.
- [Bigscreen](https://bigscreenvr.com/about/) - The social desktop-and-cinema app launched in 2016, separate from the company's headset.
- [Horizon Worlds](https://en.wikipedia.org/wiki/Horizon_Worlds) - Meta's social VR platform from December 2021, now being steered toward phones.
- [ChilloutVR](https://docs.chilloutvr.net/chilloutvr/) - A user-content-driven sandbox playable in VR and on the desktop. It has no Wikipedia article, so its own documentation is the primary source here.

## Comfort, health and accessibility

- [Virtual reality sickness](https://en.wikipedia.org/wiki/Virtual_reality_sickness) - The single biggest limit on the medium: the eyes report movement the inner ear does not, and the mismatch makes people ill.
- [Vection](https://en.wikipedia.org/wiki/Vection) - The perceptual mechanism underneath it, where peripheral motion is read by the brain as the body's own movement.
- [XR Accessibility User Requirements](https://www.w3.org/TR/xaur/) - The W3C note setting out what people with disabilities need from immersive environments. Read it before designing an interaction that assumes two hands, two eyes, a standing user or a fast reaction.
- [Virtual reality therapy](https://en.wikipedia.org/wiki/Virtual_reality_therapy) - The clinical side: exposure therapy for PTSD and phobias, plus rehabilitation after stroke and in Parkinson's disease, where engagement is the point rather than spectacle.
- [Simulator Sickness Questionnaire](https://www.tandfonline.com/doi/abs/10.1207/s15327108ijap0303_3) - Kennedy, Lane, Berbaum and Lilienthal, 1993: the instrument most VR sickness research still measures with.
- [Cybersickness literature review](https://dl.acm.org/doi/full/10.1145/3670008) - A review of cybersickness research in the ACM Digital Library.
- [Cybersickness in current headsets](https://link.springer.com/article/10.1007/s10055-021-00513-6) - A 2021 systematic review in *Virtual Reality* of causes, measurement and mitigation.
- [XR Access](https://xraccess.org/about/) - The Cornell Tech consortium, founded in 2019, building accessibility resources for XR developers.

## Enterprise and industrial VR

Where most of the continuous use has always been. These are mostly the organisations' own accounts; independent outcome studies are rarer.

### Training and simulation

- [CAE training systems](https://www.cae.com/defense-security/what-we-do/training-systems/) - The flight-simulator maker's military and civil training lines, with [CAE Sprint](https://www.cae.com/defense-security/what-we-do/training-systems/cae-sprint/) pairing a headset with physical controls.
- [Loft Dynamics](https://www.loftdynamics.com/about/) - Maker of the first VR flight simulator qualified by EASA and the FAA for real pilot training (an H125 helicopter, 2023).
- [Astronauts practise spacewalks virtually](https://blogs.nasa.gov/commercialcrew/2018/10/23/astronauts-practice-spacewalks-virtually/) - NASA's account of headset rehearsal ahead of real spacewalks.
- [Synthetic Training Environment](https://www.army.mil/article/254005/synthetic_training_environment_offers_multi_dimensional_combat_preparation) - The US Army's account of its cloud-delivered VR and AR combat training.
- [Boeing's virtual airplane](https://boeing.mediaroom.com/2025-11-06-Boeing-Pioneering-Next-Generation-Training-Tools-with-Launch-of-Virtual-Airplane) - Boeing's November 2025 pilot-procedures trainer.
- [Lockheed Martin VCCT](https://www.lockheedmartin.com/en-us/news/features/history/vcct.html) - Lockheed Martin's retrospective on its VR crew-familiarisation trainer for land vehicles, and its [immersive training devices](https://www.lockheedmartin.com/en-us/news/features/2023/immersive-training-devices-blending-real-and-simulated-worlds-together.html).
- [Strivr at Walmart](https://www.strivr.com/customers/walmart) - The vendor's case study of VR training rolled out across a retailer's stores.

### Design review and engineering

- [Ford FIVE](https://newatlas.com/ford-immersive-vehicle-environment-five-lab-vr/33952/) - Ford's Immersive Vehicle Environment, where designers walk around full-scale virtual cars before a clay model exists.
- [Varjo for automotive design](https://varjo.com/use-cases/automotive) - How the Finnish maker's high-resolution headsets are used in car design; see the [VR-1 launch](https://varjo.com/news/varjo-announces-vr-1-worlds-first-human-eye-resolution-vr-headset-for-industrial-use).
- [Autodesk VRED](https://www.autodesk.com/products/vred/overview) - Autodesk's automotive visualisation and design-review software, including review in a headset.
- [NX Immersive Explorer](https://plm.sw.siemens.com/en-US/nx/cad-online/mcad-software/nx-immersive-explorer/) - Headset design review inside Siemens NX.
- [Spatial](https://en.wikipedia.org/wiki/Spatial_%28platform%29) - Founded in 2017 for AR and VR workplace collaboration before pivoting to social spaces.

### Medicine

- [BRAVEMIND](https://ict.usc.edu/research/projects/bravemind-virtual-reality-exposure-therapy/) - USC's VR exposure therapy for post-traumatic stress, used across US veterans' and military clinics.
- [Osso VR](https://www.ossovr.com/about) - Surgical training and assessment in VR.
- [FundamentalVR](https://www.fundamentalvr.com/) - Surgical simulation combining VR with haptic feedback.
- [Johns Hopkins BME: VR training](https://www.bme.jhu.edu/hello-world/vr-training/) - Johns Hopkins Biomedical Engineering on its VR training work.

### Education and venues

- [ENGAGE XR](https://engagevr.io/) - A VR platform for classrooms and training across SteamVR, Quest and Pico headsets.
- [ClassVR](https://www.classvr.com/) - Headsets, curriculum content and classroom management for schools.
- [Zero Latency](https://en.wikipedia.org/wiki/Zero_Latency_%28company%29) - Free-roam VR arenas, founded in Melbourne in 2013.
- [Sandbox VR](https://en.wikipedia.org/wiki/Sandbox_VR) - Location-based VR with full-body motion capture, founded in 2016.

## Platforms that were switched off

Hardware outlives its platform. These are the closures, with dates, because a headset whose store is gone is the normal end state in this field rather than an exception.

- [Google Daydream](https://en.wikipedia.org/wiki/Google_Daydream) - Phone-based VR, 2016 to 2019, closed with an unusually frank admission: "there hasn't been the broad consumer or developer adoption we had hoped".
- [Samsung Gear VR](https://en.wikipedia.org/wiki/Samsung_Gear_VR) - Built with Oculus and launched in 2015, discontinued on 30 September 2020, and the reason a great many phones briefly came with a headset in the box.
- [Oculus Go](https://en.wikipedia.org/wiki/Oculus_Go) - The 2018 standalone headset, dropped in 2020 when the Quest line replaced it, with new app submissions closed first.
- [Windows Mixed Reality](https://en.wikipedia.org/wiki/Windows_Mixed_Reality) - Microsoft's platform and headset family, deprecated in December 2023 and removed from Windows 11 during 2024, leaving working hardware without an operating system that speaks to it.
- [PlayStation VR](https://en.wikipedia.org/wiki/PlayStation_VR) - The original 2016 headset, over five million sold, supported until 2024 and succeeded by PlayStation VR2.
- [The Void](https://en.wikipedia.org/wiki/The_Void_%28virtual_reality%29) - Free-roam "hyper-reality" venues built on Disney and Lucasfilm licences, 2014 to 2020, closed when the pandemic halted location-based entertainment.
- [Rec Room](https://en.wikipedia.org/wiki/Rec_Room_(video_game)) - The clearest case of all: launched on 1 June 2016, shut down on 1 June 2026, exactly ten years later, after more than 150 million players. The stated reason was not user numbers but economics — "our costs always ended up overwhelming the revenue we brought in".

## Preservation

What keeps a headset useful after its maker stops.

- [Unlocking Oculus Go](https://developers.meta.com/horizon/blog/unlocking-oculus-go/) - Meta's own release of an unlocked system build for the discontinued Go, so owners can repurpose it.
- [QuestStack](https://github.com/starseed12345/QuestStack) - A GPL tool that unlocks the bootloader of the original Meta Quest on its final firmware.
- [Oasis driver for Windows Mixed Reality](https://github.com/mbucchia/Oasis-Driver-for-Windows-Mixed-Reality) - A reverse-engineered SteamVR driver that revives Reverb, Odyssey and other WMR headsets after Microsoft removed the platform.
- [Revive](https://github.com/LibreVR/Revive) - Runs Oculus-exclusive PC games on other headsets through OpenVR.
- [OpenPSVR](https://github.com/alatnet/OpenPSVR) - An open OpenVR driver for the original PlayStation VR.
- [PSVR2Toolkit](https://github.com/BnuuySolutions/PSVR2Toolkit) - Community improvements to PlayStation VR2 on PC.
- [iVRy](https://store.steampowered.com/app/1005971/iVRy_Driver_for_SteamVR_PSVR_Premium_Edition/) - A commercial driver for using PlayStation VR headsets on PC.
- [PSMoveServiceEx](https://github.com/Timocop/PSMoveServiceEx) - A maintained fork keeping PlayStation Move controllers usable as PC trackers, built on [psmoveapi](https://github.com/thp/psmoveapi).
- [SideQuest](https://sidequestvr.com/) - Sideloading and discovery that keeps content installable outside the official Quest store.

## Communities and archives

- [Voices of VR](https://voicesofvr.com/) - An interview podcast running since 2014, an informal oral history of the field.
- [UploadVR](https://www.uploadvr.com/) - A VR news outlet since the development-kit era.
- [Road to VR](https://roadtovr.com/) - VR news since 2011.
- [r/virtualreality](https://www.reddit.com/r/virtualreality/) - The largest VR discussion subreddit. Moderation is uneven and it includes adult-oriented user content.
- [Meta Community Forums](https://communityforums.atmeta.com/) - Meta's official forums for Quest owners and developers.
- [Extended Reality: Visions of the Future](https://www.globenewswire.com/news-release/2026/09/10/3359874/28639/en/computer-history-museum-announces-extended-reality-visions-of-the-future-exhibit.html) - The Computer History Museum's XR exhibition, October 2026 to March 2027, with more than 100 artifacts from its collection, from Sutherland's head-mounted display to the Vision Pro.
- [IEEE VR](https://en.wikipedia.org/wiki/IEEE_VR) - The annual academic conference, tracing back to 1993.
- [Augmented World Expo](https://en.wikipedia.org/wiki/Augmented_World_Expo) - The annual AR and VR industry gathering since 2010.

## In fiction

Science fiction named this field's ideas before engineers built them, and it guessed wrong as often as right. Each entry says which.

- [Pygmalion's Spectacles](https://www.gutenberg.org/ebooks/22893) - Stanley G. Weinbaum's 1935 story of spectacles that put the wearer inside a film, promising "taste, smell, even touch". Right about the goal of standing inside a story; the senses beyond sight and sound are still the hard part (see awesome-stereoscopy's [Beyond the eyes](https://github.com/danielcamposramos/awesome-stereoscopy#beyond-the-eyes)).
- [The Veldt](https://en.wikipedia.org/wiki/The_Veldt_%28short_story%29) - Ray Bradbury's 1950 "nursery", a room that reproduces any place its children imagine. The room-scale part came true in the CAVE (1992, above); the part where the lions become real did not.
- [Holodeck](https://en.wikipedia.org/wiki/Holodeck) - Star Trek's simulation room, first seen as the "recreation room" in the 1974 animated episode "The Practical Joker". A shared, walk-in simulation is real; solid objects made of light and force fields are not.
- [Tron](https://en.wikipedia.org/wiki/Tron_%28film%29) - The 1982 film of a programmer pulled inside a computer. Nobody enters a computer, but the film was one of cinema's earliest uses of extensive computer-generated imagery, so its imaginary world was genuinely made of the thing it depicted.
- [Neuromancer](https://en.wikipedia.org/wiki/Neuromancer) - William Gibson's 1984 novel, building on his 1981 story "Burning Chrome": "cyberspace", "jacking in", and the "matrix" as the name of the space. The vocabulary won outright; the direct neural connection is still research (see Neuralink below).
- [The Lawnmower Man](https://en.wikipedia.org/wiki/The_Lawnmower_Man_%28film%29) - The 1992 film in which VR simulations and drugs rewire a man's brain. It brought VR headsets to a mass audience; nothing about the mechanism was real.
- [Snow Crash](https://en.wikipedia.org/wiki/Snow_Crash) - Neal Stephenson's 1992 novel and the source of "Metaverse", a word the industry revived three decades later, along with the question of who owns the space.
- [Jurassic Park's "Unix system"](https://en.wikipedia.org/wiki/File_System_Navigator) - The 1993 film's 3D control-room interface was real software shown in a fictional role: Silicon Graphics' three-dimensional file system navigator, a file browser, presented as the park's security system. The film was also the [first to show computer screens running live on camera](https://en.wikipedia.org/wiki/Jurassic_Park_%28film%29).
- [The Matrix](https://en.wikipedia.org/wiki/The_Matrix) - The 1999 film, drawing on Neuromancer among its influences: a complete world written into the brain through a socket. Brain–computer interfaces did arrive, but in the opposite direction; they read signals out, as the next two entries show.
- [BrainGate](https://en.wikipedia.org/wiki/BrainGate) - The real counterpart: in its 2004–2006 trial, published in Nature in 2006, a person with tetraplegia moved a computer cursor by thought.
- [Neuralink](https://en.wikipedia.org/wiki/Neuralink) - The company founded in June 2016 to make such implants wireless and far denser. It continues the reading direction; writing a world into the senses, as The Matrix did, remains fiction.
- [Sword Art Online](https://en.wikipedia.org/wiki/Sword_Art_Online) - Reki Kawahara's light novels from 2009, whose NerveGear helmet drives all five senses through the brain. Its social game worlds exist (see VRChat above); the helmet does not.
- [Ready Player One](https://en.wikipedia.org/wiki/Ready_Player_One) - Ernest Cline's 2011 novel: the OASIS, reached with visors and haptic gloves. The closest fiction to what actually shipped, and wrong in one telling way: it imagines one universe for everything, where this list's switched-off platforms show the opposite.

## Related lists

- [awesome-webxr](https://github.com/msub2/awesome-webxr) - VR and AR on the web: the engines, frameworks and content hubs of the browser side, which this list deliberately leaves to it.
- [awesome-stereoscopy](https://github.com/danielcamposramos/awesome-stereoscopy) - The stereo medium itself: formats, packings, signalling, stereo photography and 3D cinema. A headset is a stereoscope you wear, and that list is where the optics lead.
- [awesome-ar](https://github.com/danielcamposramos/awesome-ar) - Augmented reality: see-through optics, tracking and mapping, and the SDKs built on them.
- [awesome-vrchat](https://github.com/madjin/awesome-vrchat) - A deeper collection for VRChat content creation specifically.
- [awesome-openxr](https://github.com/Elameri/awesome-openxr) - An OpenXR-specific collection, for when the standard itself is the subject.
- [awesome-mixed-reality](https://github.com/saurabhchalke/awesome-mixed-reality) - Mixed reality development resources spanning both sides of the passthrough line.
- [awesome-visionOS](https://github.com/tomkrikorian/awesome-visionOS) - Apple's platform in depth, for the headset this list gives one entry.
- [awesome-linux-hdr](https://github.com/danielcamposramos/awesome-linux-hdr) - HDR and deep colour on Linux, from specification to photons: the display chain behind any screen, headset panels included.
- [awesome-a11y](https://github.com/brunopulis/awesome-a11y) - Accessibility resources in general, for the principles behind this list's accessibility entries.
- [awesome-digital-preservation](https://github.com/digipres/awesome-digital-preservation) - Digital preservation practice and tools, for keeping discontinued platforms, formats and their content usable.
- [awesome-volumetric-filmmaking](https://github.com/SimileSystems/awesome-volumetric-filmmaking) - Volumetric video capture and playback; dormant since 2018, still a useful map of the field.
- [awesome-light-fields](https://github.com/JoanCharmant/awesome-light-fields) - Light field capture, rendering and displays, the step beyond two views; dormant since 2016, kept for its history.

## Known gaps

Stated openly, because a list that hides its blind spots is worse than one that names them. These are the places this list is weakest, and the contributions most wanted:

**Non-Western ecosystems** now have their own history and headset sections, built from English-language sources. Coverage in the markets' own languages is still missing, as are YVR and Samsung's Galaxy XR, whose own pages could not be verified. Contributions in any language are wanted; cite what you can.

**Enterprise and industrial VR** has a section now, but it rests mostly on the organisations' own accounts. Independent outcome studies are wanted.

**Communities** are represented by their news outlets, a podcast and the main conferences. The active forums sit mostly on platforms whose pages could not be verified in the ordinary way, and an unverified link is worse than an admitted gap.

**Research literature** is still thin: the comfort entries point at one systematic review and at overviews rather than at the primary papers.

**Preserving content** lags behind preserving hardware. The drivers and unlocks in the Preservation section keep headsets working; the games and worlds of closed stores have no equivalent yet.

## Contributing

Contributions are welcome. Read the [contribution guidelines](contributing.md) first.
