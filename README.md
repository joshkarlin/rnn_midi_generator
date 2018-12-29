# MIDI Generation using Keras

Train RNN and LSTM model on MIDI files and then predict based on a random pattern from the training data. 

Hopefully this will produce something in the ballpark of music...

## Setup
1. Clone the repo.
1. Create the conda environment.
    ```
    cd <path/to/repo>
    conda env create
    conda activate music_gen
    ```
1. Run Jupyter notebook.
    ```
    jupyter notebook
    ```
1. Download some MIDI files.
    To run the code, you will need some `.mid` files in your `input` folder.

    The DOOM and DOOM II soundtracks can be downloaded from http://karthik82.tripod.com/mus_midi_doom.htm

#### Jupyter notebook pimping instructions (optional)
1. Run these commands:
    ```
    jupyter contrib nbextension install --user
    jupyter nbextensions_configurator enable
    jt -t grade3 -T
    ```

1. Go to `localhost:8888/nbextensions` and enable `autopep8`, `Collapsible Headings`, `ruler`, `Table of Contents (2)` and any others you want.

    The extensions specified above do the following:
    - `autopep8`: button & keyboard shortcut to pep8ify your code
    - `Collapsible Headings`: makes all markdown headings collapsible
    - `ruler`: a ruled line at a character position of your choice
    - `Table of Contents (2)`: provides a clickable table of contents either at the start of your notebook, floating at the side, or both
