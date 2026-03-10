# Pinger Service RPC contract

## Overview

This RPC contract is used to test the operation of the [EasyP](https://github.com/easyp-tech/easyp) tool.

The contract depends on other protos:
```yaml
deps:
  - github.com/bufbuild/protovalidate@v1.1.1                # validation 
  - github.com/googleapis/googleapis@common-protos-1_3_1    # for well-known standart types
```

There are two proto files, one includes other.
