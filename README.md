Create /etc/portage/profile/package.provided with the content:

```
sys-apps/lsb-release-1
x11-drivers/nvidia-drivers-500
sys-devel/bmake-1
```

Run the build with:

```
FEATURES=-network-sandbox ACCEPT_KEYWORDS=~amd64 emerge -av nvidia-container-toolkit
```
