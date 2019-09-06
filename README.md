A build system for debian on rockpi4 form: https://gitlab.collabora.com/rockpi/rockpi4

```
docker run --rm --interactive --tty --device /dev/kvm --workdir /recipes --mount "type=bind,source=$(pwd),destination=/recipes" --security-opt label=disable godebos/debos --scratchsize=8G rockpi4.yml
```
For some more detial reference: [Create Minimal Debian Upstream Images with Debos and Armbian](https://www.cnx-software.com/2019/06/22/create-minimal-debian-images-debos-armbian/)
