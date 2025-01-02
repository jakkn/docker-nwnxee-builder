> [!WARNING]  
> This image is outdated and superseded by NWNX: https://github.com/nwnxee/unified/pkgs/container/builder

# docker-nwnxee-builder

Builder image for NWNX: EE based on the [Dockerfile.builder](https://github.com/nwnxee/unified/blob/master/Dockerfile.builder) in the nwnxee repository.

Justification for separating the build environment from the sources is to enable versioned automated builds, that can in turn be used in a multistage build of nwnxee. Extracting the apt installs from the multistage build also sports improved build time.
