# Week 6 — Spatial audio research and accessible interaction

**Jeboy Compuesto · CART 470 · October 28, 2026**  
**Project: Concordia Soundscape Explorer**

[Back to journal](../../README.md)

## Research and contribution

This week, I focused on understanding spatial audio and researching how accessibility could shape the UI for Concordia Soundscape Explorer. I looked into the differences between Ambisonics and conventional channel-based audio to better understand the technical work happening within our team and how it connects to the user experience.

I explored [HOAST](https://hoast.iem.at/), [Cities and Memory](https://citiesandmemory.com/sound-map/), and [Radio Aporee](https://aporee.org/maps/) as references. HOAST helped me think about combining immersive visuals with directional audio, while the sound maps gave me references for organizing recordings by location. These are useful starting points for designing how someone moves from browsing campus locations to exploring an individual soundscape.

I also researched Audiokinetic's [“Visualizing Ambisonics with the 3D Meter”](https://www.audiokinetic.com/en/community/blog/visualizing-ambisonics-with-the-3d-meter/). It helped me understand why ordinary channel meters don't clearly communicate the direction of an Ambisonic sound field. The article uses a spherical heatmap to show sound levels across different directions and explains how smoothing makes changes in the display less abrupt. For our project, this gives me a reference for exploring visual feedback that helps users understand where sound is coming from. I would treat this as an optional addition alongside keyboard navigation and screen-reader support.

I researched accessibility through the [VRSight paper](https://arxiv.org/html/2508.02958v1), which explores spatial audio and scene descriptions for blind VR users. It made me consider how our project could communicate useful information beyond what appears on screen. Although our project is browser-based, this research raised relevant questions about orientation, descriptions, and user control.

## Client discussion

During our October 21 client meeting, I brought up the experience of blind and visually impaired users and asked about opportunities for testing. We discussed a list alternative to the map, keyboard navigation, screen-reader-friendly controls, and possible directional sound cues. I also asked about the tactile interface mentioned earlier, but the client encouraged us to focus on making the website itself accessible and navigable.

The technical discussion focused on continuing with Omnitone while researching HOAST and keeping the audio rendering modular. Omnitone itself supports Ambisonics; the question is which implementation fits our assets and prototype. This matters for the UI because the controls I design need to match the functionality the team can provide.

## Reflection and next steps

The main challenge is balancing these ideas with the scope of our prototype. We need to connect the existing functionality while keeping accessibility in mind as the interface develops. A visual representation of sound could help some users understand the experience, but it would not replace a way to choose locations and operate the player without relying on vision.

My work this week was research and UI ideation. My next step is to turn this research into Figma UI ideas, particularly the location list and soundscape exploration screen, and coordinate with the team so the controls match the audio functionality. I also want to follow up on potential user testing once we have an interaction flow that people can try.

## References

- [HOAST — Higher-Order Ambisonics Streaming Library](https://hoast.iem.at/)
- [Cities and Memory — Global sound map](https://citiesandmemory.com/sound-map/)
- [Radio Aporee — Maps](https://aporee.org/maps/)
- [Audiokinetic — Visualizing Ambisonics with the 3D Meter](https://www.audiokinetic.com/en/community/blog/visualizing-ambisonics-with-the-3d-meter/#id-3dmeterblogpost-smoothing)
- [VRSight: An AI-Driven Scene Description System to Improve Virtual Reality Accessibility for Blind People](https://arxiv.org/html/2508.02958v1)
- [Omnitone documentation](https://github.com/GoogleChrome/omnitone)
- October 21, 2026 client meeting, documented in my “Spatial Audio and Accessibility Research” meeting notes.
