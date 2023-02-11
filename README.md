# Growspace Sim2Real Plant Project

TODO more  instructions here.

## Setup

This repo depends heavily on the growspace simulator, which is loaded as submodule (in the `growspace` dir).

When first cloning this repo, make sure to also clone the submodule by using this command:

    git clone --recursive git@github.com:YasmeenVH/growspace2real.git

If you forgot to do the `--recursive` during cloning, you can pull the submodule later by doing this:

    git submodule update --init --recursive

---

Once you've downloaded everything, first install the growspace library

    cd growspace/
    pip install -e .

Then install the growspace2real package

    cd ../
    pip install -e .
