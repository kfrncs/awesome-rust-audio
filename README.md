# Awesome Rust Audio

There are many projects available in the [RustAudio](https://github.com/RustAudio) group, which also has a [Discourse](https://rust-audio.discourse.group/), and a [Discord](https://discord.gg/b3hjnGw). This is an effort to collect all the disparate projects and resources which may come in handy working with audio/music in Rust. Projects available in the [RustAudio Github group](https://github.com/RustAudio) will not be duplicated here, so have a look there too. Attempts have been made to only feature projects which have not been abandoned, i.e. with active development in the past year or so.

For more general resources for learning DSP, see [here](https://github.com/crsaracco/dsp-learning).

Pull requests welcome!


## Tutorials
_(note that [vst-rs](https://github.com/RustAudio/vst-rs) examples can be found [here](https://github.com/RustAudio/vst-rs/tree/master/examples))_

- [Creating a Simple Synthesizer VST Plugin in Rust](https://vaporsoft.net/creating-an-audio-plugin-with-rust-vst/) by [doomy](https://github.com/piedoom) ([repo](https://github.com/resamplr/rust-noise-vst-tutorial))
- [Writing an Audio Plugin in Rust](https://www.seventeencups.net/posts/writing-an-audio-plugin-in-rust/) (VST) by [Joe Clay](https://github.com/17cupsofcoffee) ([repo](https://github.com/17cupsofcoffee/digidist))
- [Creating a Synthesizer with Tuix](https://github.com/geom3trik/tuix_audio_synth), the [cross-platform GUI toolkit](https://github.com/geom3trik/tuix), both by [George Atkinson](https://github.com/geom3trik)


## Plugins

- [OctaSine](https://github.com/greatest-ape/OctaSine), a VST2 frequency modulation synthesizer by [Joakim Frostegård](https://github.com/greatest-ape)
- [simple-eq](https://github.com/m-hilgendorf/simple-eq) by [Mike Hilgendorf](https://github.com/m-hilgendorf)
- [rusty-compressor](https://github.com/m-hilgendorf/rusty-compressor) by [Mike Hilgendorf](https://github.com/m-hilgendorf)
- [spectral-decay](https://github.com/conundrumer/spectral-decay) by [Conundrumer](https://github.com/conundrumer)
- [baseplug](https://github.com/wrl/baseplug), a high-level model/view/controller-ish audio plugin framework by [William Light](https://github.com/wrl)

#### GUI Examples
- [imgui_baseview_test_vst2](https://github.com/DGriffin91/imgui_baseview_test_vst2), an example plugin using [baseview](https://github.com/RustAudio/baseview) and [imgui-rs](https://github.com/imgui-rs/imgui-rs) by [DGriffin91](https://github.com/DGriffin91)
- [egui_baseview_test_vst2](https://github.com/DGriffin91/egui_baseview_test_vst2), an example plugin using [baseview](https://github.com/RustAudio/baseview) and [egui](https://github.com/emilk/egui) by [DGriffin91](https://github.com/DGriffin91)
- [iced-baseplug-examples](https://github.com/BillyDM/iced-baseplug-examples), example plugins using [baseplug](https://github.com/wrl/baseplug.git) and [iced](https://github.com/hecrj/iced.git) by [BillyDM](https://github.com/BillyDM) (note: WIP)


## Standalone

- [Rudiments](https://github.com/jonasrmichel/rudiments), a step-sequencing drum machine by [Jonas Michel](https://github.com/jonasrmichel)
- [Oscen](https://github.com/reedrosenbluth/oscen), a library for building modular synthesizers by [Reed Rosenbluth](https://github.com/reedrosenbluth)
- [synthesizer-io](https://github.com/raphlinus/synthesizer-io) by [Raph Levien](https://github.com/raphlinus)
- [midir](https://github.com/Boddlnagg/midir), a cross-platform realtime MIDI library by [Patrick Reisert](https://github.com/Boddlnagg)

#### Linux Only
- [loopers](https://github.com/mwylde/loopers), a graphic live looper by [Micah Wylde](https://github.com/mwylde)
- [mixjack](https://github.com/derekdreery/mixjack), a mixer for JACK using [Druid](https://github.com/linebender/druid) by [Richard Dodd](https://github.com/derekdreery) 
- [maschine.rs](https://github.com/wrl/maschine.rs), open-source handling for Maschine Mikro mk2 by [William Light](https://github.com/wrl)
- [alsa-rs](https://github.com/diwic/alsa-rs), ALSA bindings for Rust by [diwic](https://github.com/diwic)
