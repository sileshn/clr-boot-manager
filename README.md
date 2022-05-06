![](https://github.com/Fubuchi/clr-boot-manager/actions/workflows/main.yml/badge.svg)

Patched version of [clr-boot-manager](https://github.com/clearlinux/clr-boot-manager) to prevent it outputs errors while using in WSL

Errors for references:
- clr-boot-manager repo: [#140](https://github.com/clearlinux/clr-boot-manager/issues/140)
- SolusWSL repo: [link](https://github.com/sileshn/SolusWSL#features-and-important-information)

What the patch does:
- Simply return true in some kernel check functions to prevent them output errors
