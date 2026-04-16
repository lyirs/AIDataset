# Music-Audio

Music audio, MIR, transcription, source separation, tagging, and symbolic-audio learning datasets.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | NSynth | Audio | [Site](https://magenta.tensorflow.org/datasets/nsynth) | CC BY 4.0 | Neural audio synthesis and music representation learning | [Paper](https://arxiv.org/abs/1704.01279) | A foundational music-audio dataset for controllable synthesis and representation learning. |
| 2 | MAESTRO | Audio + MIDI | [Site](https://magenta.tensorflow.org/datasets/maestro) | CC BY-NC-SA 4.0 | Piano transcription and symbolic-audio music modeling | [Paper](https://arxiv.org/abs/1810.12247) | One of the most standard modern datasets for piano transcription and music generation. |
| 3 | MUSDB18 | Audio | [Site](https://sigsep.github.io/datasets/musdb.html) | Mixed / track-specific CC terms | Music source separation and demixing evaluation | [Paper](https://arxiv.org/abs/1804.06267) | The default benchmark family for modern music source separation papers. |
| 4 | FMA (Free Music Archive) | Audio | [GitHub](https://github.com/mdeff/fma) | Mixed / artist-chosen audio licenses + metadata CC BY 4.0 | Music genre classification and open MIR baselines | [Paper](https://arxiv.org/abs/1612.01840) | A classic open MIR benchmark with full-length audio and metadata. |
| 5 | MTG-Jamendo Dataset | Audio | [Site](https://mtg.github.io/mtg-jamendo-dataset/) | Mixed / metadata CC BY-NC-SA 4.0 + track-specific CC audio | Music auto-tagging, mood/theme, genre, and instrument detection | [Paper](https://archives.ismir.net/ismir2019/paper/000055.pdf) | A high-signal music-tagging benchmark used far beyond genre-only setups. |
| 6 | MagnaTagATune | Audio | [Site](https://mirg.city.ac.uk/codeapps/the-magnatagatune-dataset) | Unknown | Music tagging and auto-annotation | [Paper](https://archives.ismir.net/ismir2009/paper/000044.pdf) | A classic large-scale music tagging dataset still cited in MIR and audio tagging work. |
| 7 | Slakh2100 | Audio + MIDI | [Site](https://www.slakh.com/) | Unknown | Multitrack music source separation and transcription | [Paper](https://archives.ismir.net/ismir2019/paper/000036.pdf) | A widely used synthetic multitrack music dataset for separation, transcription, and music generation. |
| 8 | OpenMIC-2018 | Audio | [Site](https://zenodo.org/records/1432913) | CC BY 4.0 | Polyphonic instrument recognition | [Paper](https://ismir2018.ircam.fr/doc/pdfs/248_Paper.pdf) | A standard open benchmark for instrument tagging in music mixtures. |
| 9 | MusicNet | Audio + labels | [Site](https://zenodo.org/records/5120004) | CC BY 4.0 | Supervised music transcription and note-level labeling | [Paper](https://arxiv.org/abs/1611.09827) | One of the most cited classical-music datasets for note transcription and representation learning. |
| 10 | IRMAS | Audio | [Site](https://www.upf.edu/web/mtg/irmas) | CC BY-NC-SA 3.0 | Predominant instrument recognition | [Paper](https://ismir2012.ismir.net/event/papers/049-ismir-2012.pdf) | A canonical benchmark for instrument recognition in real musical mixtures. |
| 11 | VocalSet | Audio | [Site](https://zenodo.org/records/1442513) | CC BY 4.0 | Singing voice modeling and technique classification | [Paper](https://arxiv.org/abs/1804.05080) | One of the strongest open singing-voice datasets for voice technique, timbre, and synthesis research. |
| 12 | RWC Music Database | Audio + MIDI + lyrics | [Site](https://staff.aist.go.jp/m.goto/RWC-MDB/) | Custom / research-use application | MIR benchmarking across genre, instruments, and full songs | [Docs](https://staff.aist.go.jp/m.goto/RWC-MDB/) | A historic large-scale music benchmark family that still shows up in MIR baselines and evaluation tables. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [Audio-Understanding overview](../Audio-Understanding/README.md)
- [MIREX](https://www.music-ir.org/mirex/wiki/MIREX_HOME)
- [MUSDB18](https://sigsep.github.io/datasets/musdb.html)
- [OpenMIC-2018](https://zenodo.org/records/1432913)

## Selection Note

- This category was split out from `Audio-Understanding` because music MIR, transcription, tagging, source separation, and singing-voice research now form a distinct high-volume subfield.
- General sound events, audio captioning, and broader audio-language resources remain in [Audio-Understanding](../Audio-Understanding/README.md).
