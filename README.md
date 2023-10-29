# sh.vinnie.work
General Purpose Utility Script

Run with curl:

```sh
curl -s https://sh.vinnie.work | sh -s --
```

Run with wget:

```sh
wget -qO- https://sh.vinnie.work | sh -s --
```

Test locally with:

```
cat site/index.html | sh -s --
```

## Git Sparse Checkout

Pre-Req: This requires the use of sudo.

Checkout specific folders from a git repository.

## User Git Clone

Pre-Req: This requires the use of sudo.

Clone a git repository into a folder not owned by the user. For example, if you wanted to clone `crazychenz/sh.vinnie.work.git` into `/opt/sh.vinnie.work` and have `/opt` owned by root and `/opt/sh.vinnie.work` owned by a target user.