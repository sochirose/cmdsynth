# cmdSynth

cmdSynth is a powerful and intuitive command line synthesizer designed for musicians, sound designers, and developers. It allows users to create, manipulate, and experiment with sound directly from the terminal, providing a streamlined workflow for generating audio without the need for a graphical interface.

## Features

- **Easy to Use**: Simple command syntax for quick sound creation.
- **Flexible Sound Generation**: Supports various waveforms including sine, square, triangle, and sawtooth.
- **Real-time Modulation**: Apply effects such as ADSR envelope, filters, and LFOs on the fly.
- **Extensive Parameter Control**: Fine-tune frequency, amplitude, phase, and more.
- **Scriptable**: Automate sound synthesis with scripts for complex soundscapes.
- **Portable**: Lightweight and runs on any system with a command line interface.

## Installation

To install cmdSynth, clone the repository and run the setup script:

```bash
git clone https://github.com/sochiyuzuki/cmdsynth.git
cd cmdsynth
./setup.sh
```

## Usage

Create a simple sine wave tone:
```bash
cmdsynth --wave sine --freq 440 --duration 5
```

Apply an ADSR envelope:
```bash
cmdsynth --wave square --freq 440 --duration 5 --adsr 0.1,0.2,0.7,0.3
```

Add a low-pass filter:
```bash
cmdsynth --wave sawtooth --freq 440 --duration 5 --filter lowpass --cutoff 1000
```

## Documentation

For detailed documentation, including a full list of commands and options, please refer to the [cmdSynth Wiki](https://github.com/sochiyuzuki/cmdsynth/wiki).

## Contributing

We welcome contributions from the community! If you find a bug or have an idea for an improvement, please open an issue or submit a pull request.

## License

cmdSynth is released under the MIT License. See the [LICENSE](https://github.com/sochiyuzuki/cmdsynth/blob/main/LICENSE) file for more details.

---
