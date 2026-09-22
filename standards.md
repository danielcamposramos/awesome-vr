# VR standards and primary references

The specifications, registries and reference implementations behind the
[readme](readme.md)'s standards section. Normative behaviour comes from the
specification, implementation behaviour from a named runtime or driver, and an
organisation's status from its own site. This file links; it does not host
copies.

## Device and runtime APIs

### OpenXR (Khronos)

- [Registry and specification](https://registry.khronos.org/OpenXR/)
- [1.0 announcement, July 2019](https://www.khronos.org/news/press/khronos-releases-openxr-1.0-specification-establishing-a-foundation-for-the-ar-and-vr-ecosystem)
- [OpenXR-SDK-Source](https://github.com/KhronosGroup/OpenXR-SDK-Source)

The loader is the part worth being precise about: it finds the active runtime
on a system and hands control to it (Monado, SteamVR or a vendor's own). An
application linking against OpenXR links against the loader, not a runtime.

### OpenVR (Valve)

- [Source: SDK, API and samples](https://github.com/ValveSoftware/openvr)

It predates OpenXR and remains what most SteamVR-era titles speak;
OpenComposite translates between the two.

### WebXR (W3C)

- [Device API](https://www.w3.org/TR/webxr/)
- [Hand Input Module](https://www.w3.org/TR/webxr-hand-input-1/)
- [Immersive Web groups](https://www.w3.org/immersive-web/)

The Hand Input module writes privacy into its normative text: articulated hand
data needs explicit consent.

### VRPN and OSVR

- [VRPN](https://github.com/vrpn/vrpn) - Device-independent VR peripheral
  access, from UNC in the 1990s and still maintained.
- [OSVR](https://github.com/OSVR) - Razer and Sensics's open platform. Its
  osvr.org domain no longer resolves; the GitHub organisation is what remains.

## Scene and asset interchange

- [glTF](https://www.khronos.org/gltf/) and its
  [extensions registry](https://github.com/KhronosGroup/glTF/tree/main/extensions)
- [KTX 2.0 with Basis Universal](https://www.khronos.org/ktx/)
- [Vulkan](https://www.khronos.org/vulkan/)

The formats form a lineage: [VRML](https://en.wikipedia.org/wiki/VRML) (1994),
then [COLLADA](https://en.wikipedia.org/wiki/COLLADA) (Sony, later Khronos) and
[X3D](https://www.web3d.org/x3d/what-x3d) (ISO, from the
[Web3D Consortium](https://en.wikipedia.org/wiki/Web3D_Consortium)) in parallel,
then glTF as the runtime delivery format most engines now target.

## Immersive media

- [MPEG-I](https://www.mpeg.org/standards/MPEG-I/) - ISO/IEC 23090: OMAF for
  omnidirectional media ([ISO catalogue](https://www.iso.org/standard/73310.html)),
  immersive audio, and point-cloud and volumetric video.
- [AmbiX](https://ambisonics.iem.at/proceedings-of-the-ambisonics-symposium-2011/ambix-a-suggested-ambisonics-format) -
  The 2011 paper defining the Ambisonics channel order and normalisation most
  VR audio tools assume.

## Standards bodies and coordination

- [ISO/IEC JTC 1/SC 24](https://en.wikipedia.org/wiki/ISO/IEC_JTC_1/SC_24) -
  Computer graphics, VR, AR and mixed reality; its
  [secretariat history page](https://jtc1info.org/sd-2-history/jtc1-subcommittees/sc-24/)
  names the mixed and augmented reality standards ISO/IEC 18038, 18039 and
  18040, which [awesome-ar's standards](https://github.com/danielcamposramos/awesome-ar/blob/main/standards.md)
  covers.
- [IEEE VR/AR Advisory Board](https://standards.ieee.org/industry-connections/activities/vr-ar-advisory-board/) -
  The umbrella for the IEEE 2048 family, of which
  [2048.101-2023](https://standards.ieee.org/ieee/2048.101/10390/) is the part
  confirmed active.
- [Metaverse Standards Forum](https://metaverse-standards.org/) - Coordination
  across standards bodies; it publishes no standards of its own.
