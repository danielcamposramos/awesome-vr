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
- [Engines and toolkits](#engines-and-toolkits)
- [Media formats](#media-formats)
- [Social platforms](#social-platforms)
- [Comfort, health and accessibility](#comfort-health-and-accessibility)
- [Platforms that were switched off](#platforms-that-were-switched-off)
- [Related lists](#related-lists)
- [Known gaps](#known-gaps)

## History

- [Sensorama](https://en.wikipedia.org/wiki/Sensorama) - Morton Heilig's 1962 machine, one of the earliest known examples of immersive multi-sensory technology: a stereoscopic display with stereo sound, fans, odour emitters and a motion chair, aimed at a single seated viewer.
- [Morton Heilig](https://en.wikipedia.org/wiki/Morton_Heilig) - The cinematographer who wanted to build the "cinema of the future", and who patented the Telesphere Mask, a head-mounted stereoscopic viewer with sound, in 1960, years before anyone had a computer to drive one.
- [The Sword of Damocles](https://en.wikipedia.org/wiki/The_Sword_of_Damocles_(virtual_reality)) - The 1968 head-mounted display built by Ivan Sutherland with Bob Sproull, Quintin Foster and Danny Cohen, and the first to redraw its image from the viewer's tracked head pose. It hung from the ceiling because it was too heavy to wear, and Sutherland described the leap plainly: "we didn't need a camera – we could substitute a computer".
- [Ivan Sutherland](https://en.wikipedia.org/wiki/Ivan_Sutherland) - The computer-graphics pioneer behind that display, and behind much of the vocabulary the field still uses.
- [VPL Research](https://en.wikipedia.org/wiki/VPL_Research) - Founded in 1984, one of the first companies to develop and sell virtual reality products: the DataGlove, the EyePhone head-mounted display, the DataSuit and the RB2 system.
- [Jaron Lanier](https://en.wikipedia.org/wiki/Jaron_Lanier) - Co-founder of VPL with Thomas Zimmerman, and the person most responsible for the phrase "virtual reality" reaching the public.
- [NASA VIEW](https://ntrs.nasa.gov/citations/19950007621) - The Virtual Environment Workstation at NASA Ames, where Scott Fisher, Michael McGreevy and Warren Robinett assembled a head-mounted display partly from a motorcycle helmet and drove it with the first dataglove used in VR. NASA's own technical report is the primary record.
- [Cave automatic virtual environment](https://en.wikipedia.org/wiki/Cave_automatic_virtual_environment) - The CAVE, introduced in 1992 at the University of Illinois Chicago: projectors aimed at between three and six walls of a room-sized cube, the answer to headsets that put several people inside the same scene.
- [Virtuality Group](https://en.wikipedia.org/wiki/Virtuality_Group) - The British company that put VR in arcades from 1987, went bankrupt in 1997, and is the reason a generation met the medium standing in a ring with a visor on.
- [Sega VR](https://en.wikipedia.org/wiki/Sega_VR) - Announced in 1991 and cancelled in 1994. The stated reason is worth remembering: the effect was judged "too realistic", so players might move while wearing it and hurt themselves.
- [Forte VFX1](https://en.wikipedia.org/wiki/Forte_VFX1) - The 1995 consumer headset that actually shipped: helmet, handheld controller and an ISA card, with head tracking, stereoscopic 3D and stereo audio.
- [Oculus Rift](https://en.wikipedia.org/wiki/Oculus_Rift) - The 2012 development kit that restarted the category and set the shape of everything in the next section.

## Headsets

- [Meta Quest](https://en.wikipedia.org/wiki/Meta_Quest) - The standalone line that made headsets a mass product, and the largest headset platform in the world as of 2025. The Quest, Quest 2 and Quest Pro are already discontinued, which is the pattern this list keeps pointing at.
- [Meta Quest 3](https://en.wikipedia.org/wiki/Meta_Quest_3) - Released in October 2023 on a Snapdragon XR2 Gen 2, with colour passthrough that made mixed reality ordinary on a consumer headset.
- [PlayStation VR2](https://en.wikipedia.org/wiki/PlayStation_VR2) - Sony's 2023 headset: dual OLED panels at 2000×2040 per eye, 110° field of view, and eye tracking used for foveated rendering rather than only for input.
- [Apple Vision Pro](https://en.wikipedia.org/wiki/Apple_Vision_Pro) - Released in February 2024 at roughly 3660×3200 per eye, driven by an M-series chip paired with a dedicated R1 for sensor fusion, and unlocked by iris recognition.
- [Steam Frame](https://en.wikipedia.org/wiki/Steam_Frame) - Valve's standalone headset, announced in November 2025 and launched on 14 September 2026. Unlike the Index it needs no base stations, tracking itself from onboard cameras.
- [Valve Index](https://en.wikipedia.org/wiki/Valve_Index) - The 2019 PC headset built around Lighthouse base stations and the finger-tracking Knuckles controllers, discontinued in November 2025. Read it against the Steam Frame above: that pair is the whole industry's move from external tracking to onboard.
- [HTC Vive](https://en.wikipedia.org/wiki/HTC_Vive) - The 2016 headset, built with Valve, that introduced room-scale tracking to consumers: photosensors on the headset and controllers timed against laser sweeps from base stations in the corners of the room.
- [Bigscreen Beyond](https://en.wikipedia.org/wiki/Bigscreen_Beyond) - A 127-gram tethered headset whose face gasket is 3D-printed from a scan of the buyer's own face, discontinued in March 2025 in favour of a second version.
- [Varjo](https://en.wikipedia.org/wiki/Varjo) - The Finnish maker of high-resolution headsets for simulation and industry, founded in 2016 by former Nokia and Microsoft engineers, at clarity well beyond consumer hardware.
- [Pimax](https://en.wikipedia.org/wiki/Pimax) - The Shanghai maker that chased field of view first, shipping very wide, high-resolution PC headsets since its 2017 crowdfunding campaign.

## Tracking and rendering

- [Positional tracking](https://en.wikipedia.org/wiki/Positional_tracking) - How a headset knows where it is. Outside-in tracking watches the headset from fixed sensors in the room; inside-out puts the cameras on the headset and has it look outward, which is why current hardware ships without base stations.
- [Eye tracking](https://en.wikipedia.org/wiki/Eye_tracking) - In headsets it is an input and a budget: knowing where the eye is looking lets the renderer spend its pixels there.
- [Foveated rendering](https://en.wikipedia.org/wiki/Foveated_rendering) - The technique that follows from it, rendering at full detail only where the eye is pointed. Combined with sparse rendering and learned reconstruction it can cut the pixels actually drawn by an order of magnitude.

## Open standards and formats

- [OpenXR](https://en.wikipedia.org/wiki/OpenXR) - The Khronos standard, released as 1.0 in July 2019, that replaced one vendor API per headset. Everything in the next section depends on it.
- [OpenVR](https://en.wikipedia.org/wiki/OpenVR) - Valve's SDK and API, public since April 2015 and the default runtime interface for SteamVR, which is why so many existing games speak it rather than OpenXR.
- [WebXR](https://en.wikipedia.org/wiki/WebXR) - Stereo rendering and tracking in the browser, maintained by the W3C Immersive Web groups as the successor to WebVR.
- [WebXR Device API](https://www.w3.org/TR/webxr/) - The specification itself, for when the question is what a runtime is actually required to do.
- [Khronos Group](https://en.wikipedia.org/wiki/Khronos_Group) - The consortium of over 180 member companies behind OpenXR, glTF and Vulkan, and the reason those standards are royalty-free.
- [glTF](https://en.wikipedia.org/wiki/GlTF) - The Khronos transmission format that most XR content pipelines settle on.
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
- [Linux VR Adventures](https://vronlinux.org/) - The community wiki collecting the guides, hardware notes and workarounds that make the above usable.

## Engines and toolkits

- [Godot XR](https://docs.godotengine.org/en/stable/tutorials/xr/index.html) - The engine's own XR documentation, covering OpenXR setup, action maps and hand and body tracking, in a fully free engine.
- [StereoKit](https://stereokit.net/) - A C# and C++ framework that targets any OpenXR runtime, from Quest and HoloLens 2 to Monado on Linux, and prioritises XR application development over general engine features.
- [Unity XR Interaction Toolkit](https://docs.unity3d.com/Packages/com.unity.xr.interaction.toolkit@3.6/manual/index.html) - Unity's component-based interaction system for building VR and AR experiences.
- [Unreal Engine OpenXR](https://dev.epicgames.com/documentation/en-us/unreal-engine/developing-for-head-mounted-experiences-with-openxr-in-unreal-engine) - Epic's documentation for head-mounted development against OpenXR rather than per-vendor plugins.

## Media formats

- [360-degree video](https://en.wikipedia.org/wiki/360-degree_video) - A recording of every direction at once, shot with an omnidirectional camera or a rig. Worth being precise about: the viewpoint is fixed and the scene is not interactive, so it is watched in a headset without being virtual reality in the full sense.
- [Volumetric video](https://en.wikipedia.org/wiki/Volumetric_video) - Captured scenes a viewer can move through with six degrees of freedom, which is what 360° video is not.
- [Ambisonics](https://en.wikipedia.org/wiki/Ambisonics) - Full-sphere, speaker-independent sound. Its scene can be rotated to match the viewer's head and then decoded to binaural stereo, which is what makes audio hold still while the world turns.

## Social platforms

- [VRChat](https://en.wikipedia.org/wiki/VRChat) - The 2014 platform where users meet as their own 3D avatars in worlds other users built, and still the centre of gravity for social VR.
- [Resonite](https://en.wikipedia.org/wiki/Resonite) - Released in October 2023 as the successor to NeosVR, after its creator left that project in a dispute over cryptocurrency features. Its design principle is that virtually all content can be remixed and edited in real time, inside the session.
- [ChilloutVR](https://docs.chilloutvr.net/chilloutvr/) - A user-content-driven sandbox playable in VR and on the desktop. It has no Wikipedia article, so its own documentation is the primary source here.

## Comfort, health and accessibility

- [Virtual reality sickness](https://en.wikipedia.org/wiki/Virtual_reality_sickness) - The single biggest limit on the medium: the eyes report movement the inner ear does not, and the mismatch makes people ill.
- [Vection](https://en.wikipedia.org/wiki/Vection) - The perceptual mechanism underneath it, where peripheral motion is read by the brain as the body's own movement.
- [XR Accessibility User Requirements](https://www.w3.org/TR/xaur/) - The W3C note setting out what people with disabilities need from immersive environments. Read it before designing an interaction that assumes two hands, two eyes, a standing user or a fast reaction.
- [Virtual reality therapy](https://en.wikipedia.org/wiki/Virtual_reality_therapy) - The clinical side: exposure therapy for PTSD and phobias, plus rehabilitation after stroke and in Parkinson's disease, where engagement is the point rather than spectacle.

## Platforms that were switched off

Hardware outlives its platform. These are the closures, with dates, because a headset whose store is gone is the normal end state in this field rather than an exception.

- [Google Daydream](https://en.wikipedia.org/wiki/Google_Daydream) - Phone-based VR, 2016 to 2019, closed with an unusually frank admission: "there hasn't been the broad consumer or developer adoption we had hoped".
- [Samsung Gear VR](https://en.wikipedia.org/wiki/Samsung_Gear_VR) - Built with Oculus and launched in 2015, discontinued on 30 September 2020, and the reason a great many phones briefly came with a headset in the box.
- [Oculus Go](https://en.wikipedia.org/wiki/Oculus_Go) - The 2018 standalone headset, dropped in 2020 when the Quest line replaced it, with new app submissions closed first.
- [Windows Mixed Reality](https://en.wikipedia.org/wiki/Windows_Mixed_Reality) - Microsoft's platform and headset family, deprecated in December 2023 and removed from Windows 11 during 2024, leaving working hardware without an operating system that speaks to it.
- [PlayStation VR](https://en.wikipedia.org/wiki/PlayStation_VR) - The original 2016 headset, over five million sold, supported until 2024 and succeeded by PlayStation VR2.
- [Rec Room](https://en.wikipedia.org/wiki/Rec_Room_(video_game)) - The clearest case of all: launched on 1 June 2016, shut down on 1 June 2026, exactly ten years later, after more than 150 million players. The stated reason was not user numbers but economics — "our costs always ended up overwhelming the revenue we brought in".

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

**Non-Western ecosystems.** Pico, DPVR, Skyworth and the Chinese, Japanese and Korean headset markets are absent, and so is their coverage in their own languages. Contributions in any language are wanted; cite what you can.

**Enterprise and industrial VR** — training, simulation and design review — is barely represented, though it is where much of the money and most of the continuous use has always been.

**Communities** are not listed yet. The active ones sit mostly on platforms whose pages could not be verified in the ordinary way, and an unverified link is worse than an admitted gap.

**Research literature** is out of scope for now. The perception and comfort entries point at overviews rather than at the primary papers.

**Preservation tooling** is missing. No good source was found for community efforts to keep discontinued headsets and their stores usable, as distinct from documenting that they closed.

## Contributing

Contributions are welcome. Read the [contribution guidelines](contributing.md) first.
