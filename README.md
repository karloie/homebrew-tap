# 🍺 homebrew-tap

Custom Homebrew tap for karloie projects.

## Installation

Tap this repository:

```bash
brew tap karloie/tap
```

## Available Casks

### [kompass](https://github.com/karloie/kompass)

[![Go Version](https://img.shields.io/github/go-mod/go-version/karloie/kompass)](go.mod)
[![Go Reference](https://pkg.go.dev/badge/github.com/karloie/kompass.svg)](https://pkg.go.dev/github.com/karloie/kompass)
[![Go Report Card](https://goreportcard.com/badge/github.com/karloie/kompass)](https://goreportcard.com/report/github.com/karloie/kompass)
[![CI](https://github.com/karloie/kompass/actions/workflows/ci.yml/badge.svg)](https://github.com/karloie/kompass/actions/workflows/ci.yml)
[![Homebrew Version](https://img.shields.io/badge/dynamic/regex?url=https%3A%2F%2Fraw.githubusercontent.com%2Fkarloie%2Fhomebrew-tap%2Fmain%2FCasks%2Fkompass.rb&search=version%20%22(%3F%3Cversion%3E%5B%5E%22%5D%2B)%22&replace=%24%3Cversion%3E&label=homebrew)](https://github.com/karloie/homebrew-tap)
[![Docker Pulls](https://img.shields.io/docker/pulls/karloie/kompass)](https://hub.docker.com/r/karloie/kompass)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Kubernetes cluster visualization and exploration tool.

```bash
brew install karloie/tap/kompass
```

### [bastille](https://github.com/karloie/bastille)

[![Go Version](https://img.shields.io/github/go-mod/go-version/karloie/bastille)](go.mod)
[![Go Reference](https://pkg.go.dev/badge/github.com/karloie/bastille.svg)](https://pkg.go.dev/github.com/karloie/bastille)
[![Go Report Card](https://goreportcard.com/badge/github.com/karloie/bastille)](https://goreportcard.com/report/github.com/karloie/bastille)
[![CI](https://github.com/karloie/bastille/actions/workflows/ci.yml/badge.svg)](https://github.com/karloie/bastille/actions/workflows/ci.yml)
[![Homebrew Version](https://img.shields.io/badge/dynamic/regex?url=https%3A%2F%2Fraw.githubusercontent.com%2Fkarloie%2Fhomebrew-tap%2Fmain%2FCasks%2Fbastille.rb&search=version%20%22(%3F%3Cversion%3E%5B%5E%22%5D%2B)%22&replace=%24%3Cversion%3E&label=homebrew)](https://github.com/karloie/homebrew-tap)
[![Docker Pulls](https://img.shields.io/docker/pulls/karloie/bastille)](https://hub.docker.com/r/karloie/bastille)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

```bash
brew install karloie/tap/bastille
```

## Usage

After installation, the binaries will be available in your PATH:

```bash
kompass --help
bastille --help
```

## Updating

To update to the latest versions:

```bash
brew update
brew upgrade kompass
brew upgrade bastille
```
