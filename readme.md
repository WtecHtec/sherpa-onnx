# 准备
[可参考](https://github.com/k2-fsa/sherpa-onnx/issues/1368)

总结下来就一下几点

1. bridging_header.h 文件
如果有这个文件加入一下代码：
```
#ifndef SWIFT_API_EXAMPLES_SHERPAONNX_BRIDGING_HEADER_H_
#define SWIFT_API_EXAMPLES_SHERPAONNX_BRIDGING_HEADER_H_

#import "sherpa-onnx/c-api/c-api.h"

#endif  // SWIFT_API_EXAMPLES_SHERPAONNX_BRIDGING_HEADER_H_

```
否则创建新的文件，并加入代码，以及配置。 [可参考](https://github.com/k2-fsa/sherpa-onnx/issues/1368)

2. SherpaOnnx.swift 文件
[文件下载](https://github.com/WtecHtec/WorkNotes/blob/master/SherpaOnnx/SherpaOnnx.swift), 并且复制到项目中即可。


# 安装
本项目用于macos安装sherpa onnx 的xcframework

SPM 下载地址：
```
https://github.com/WtecHtec/sherpa-onnx.git

```
