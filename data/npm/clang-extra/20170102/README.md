## Overview
[`clang-extra`](https://www.npmjs.com/package/clang-extra) installs LLVM's clang-extra tools.

Affected versions of the package are vulnerable to Man in the Middle (MitM) attacks due to downloading resources over an insecure protocol. Without a secure connection, it is possible for an attacker to intercept this connection and alter the packages received. In serious cases, this may even lead to Remote Code Execution (RCE) on your host server.

## Remediation
There is no fix version for `clang-extra`.

## References
- [Vulnerable Code](https://github.com/Qix-/clang-extra-npm/blob/master/install-clang-extra.sh#L4)
