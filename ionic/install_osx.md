# Binary Installation on MacOS

All the Ionic binaries are available in Big Sur and Monterey using the
[homebrew package manager](https://brew.sh/).

The homebrew tool can be installed using:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

After installing the homebrew package manager, Gazebo Ionic can be installed running:

```bash
brew tap osrf/simulation
brew install gz-ionic
```

All libraries should be ready to use and the `gz sim -s` server app ready to be executed.

Head back to the [Getting started](getstarted)
page to start using Gazebo!

## Uninstalling binary install

If you need to uninstall Gazebo or switch to a source-based install once you
have already installed the library from binaries, run the following command:

```bash
brew uninstall gz-ionic
```

## Troubleshooting

See [Troubleshooting](troubleshooting.md#macos)
