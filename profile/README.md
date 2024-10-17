Hi, and welcome to **Sceners**, a historical collection of program source codes created by the Scene and curated by *[Defacto2](https://defacto2.net)*.

- [Software tools](https://defacto2.net/files/tool)
- [Scene Demos](https://defacto2.net/files/demoscene)
- [Magazines on the Scene](https://defacto2.net/magazine)

Contained within are over a 150 source code repositories that commonly target the Intel (x86) PC platform using: 

- [C](https://github.com/orgs/sceners/repositories?q=&type=all&language=c)
- [Assembly](https://github.com/orgs/sceners/repositories?q=&type=all&language=assembly)
- [Pascal](https://github.com/orgs/sceners/repositories?q=&type=all&language=pascal)

Some of the older applications and tools may only compile on Microsoft [DOS](https://winworldpc.com/product/ms-dos/1x) or specific versions of Microsoft [16-bit Windows](https://winworldpc.com/product/windows-3/31).

The original packages, archives, and preview screens are on [Defacto2](https://defacto2.net/files/github).

---

### Clone all the repositories

You can clone all the repositories on Sceners using a Bash shell and [gh](https://cli.github.com/), GitHub's command line tool.

[source](https://stackoverflow.com/questions/19576742/how-to-clone-all-repos-at-once-from-github)

```sh
# all the repositories are cloned into the subdirectory named sceners

cd ~

# iterate and clone every repository within sceners
# make sure to copy-and-paste all three lines of the loop as a single command

gh repo list sceners --limit 1000 | while read -r repo _; do
gh repo clone "$repo" "$repo"
done
```

> [!TIP] 
> The collection uses over 2.1G.
