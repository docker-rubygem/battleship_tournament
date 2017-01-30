[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/battleship_tournament.svg)](https://hub.docker.com/r/rubygem/battleship_tournament/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/battleship_tournament.svg)](https://hub.docker.com/r/rubygem/battleship_tournament/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/battleship_tournament.svg)](https://hub.docker.com/r/rubygem/battleship_tournament/)
[![Gem Downloads](https://img.shields.io/gem/dt/battleship_tournament.svg)](https://rubygems.org/gems/battleship_tournament/)
# battleship_tournament

Auto-Generated Docker image for battleship_tournament to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/battleship_tournament`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/battleship_tournament`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/battleship_tournament`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/battleship_tournament/)
