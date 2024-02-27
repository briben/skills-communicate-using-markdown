# Header 1

## Yaktocat

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

Codeblock
```sh
docker run --rm --entrypoint="/usr/bin/pwsh" -v ${PWD}:/tmp vmware/powerclicore -command /tmp/satellite_blacklist.ps1 -vCSA VCSA[, VCSA...]  | tail -n +11
```
