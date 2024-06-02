Welcome to [Defacto2's](https://defacto2.net) historical collection of code sources for [tools](https://defacto2.net/file/list?platform=-&section=programmingtool), [demos](https://defacto2.net/file/list?platform=-&section=demo), [intros](https://defacto2.net/file/list?platform=-&section=releaseAdvert), and [magazines](https://defacto2.net/file/list?platform=-&section=magazine) made for the Scene. These code repositories commonly target the Intel PC platform using [x86 Assembly](https://github.com/orgs/sceners/repositories?q=&type=all&language=assembly&sort=), [Pascal](https://github.com/orgs/sceners/repositories?q=&type=all&language=pascal&sort=), or [C](https://github.com/orgs/sceners/repositories?q=&type=all&language=c&sort=), and some sources may only compile on [PC](https://winworldpc.com/product/pc-dos/1x)/[MS-DOS](https://winworldpc.com/product/ms-dos/1x) or specific versions of [16-bit Microsoft Windows](https://winworldpc.com/product/windows-3/31).

The original packages, archives and preview screen captures are [@ Defacto2 file/list/github](https://defacto2.net/file/list/github)

[Feel free to get in contact](https://defacto2.net/contact).

---

### Clone all the repositories

You can clone all the repositories on sceners using a Bash-compatible shell with [GitHub's official command line tool](https://cli.github.com/).

> [!NOTE]
> The collection requires 2.1G

```sh
# all the repositories are cloned into the subdirectory named sceners
cd ~

# iterate and clone every repository within sceners
# make sure to copy-and-paste all three lines of the loop as a single command
gh repo list sceners --limit 1000 | while read -r repo _; do
gh repo clone "$repo" "$repo"
done
```

[clone commands source](https://stackoverflow.com/questions/19576742/how-to-clone-all-repos-at-once-from-github)
