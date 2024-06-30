# Musical Mistral

# How to Setup

```sh
# https://github.com/bzamecnik/midi2audio/blob/master/install_fluidsynth_with_soundfonts_osx.sh
brew install fluid-synth
# Download & extract
# http://www.musescore.org/download/fluid-soundfont.tar.gz
# Copy FluidR3_GM/FluidR3_GM.sf2 to /opt/homebrew/Cellar/fluid-synth/2.3.5/share/soundfonts/default.sf2
ln -s /opt/homebrew/Cellar/fluid-synth/2.3.5/share/soundfonts/default.sf2 ~/.fluidsynth/default_sound_font.sf2
```