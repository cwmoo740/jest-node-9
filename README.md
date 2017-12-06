`jest` fails on node 9.

```
/usr/bin/node[23762]: ../src/node_file.cc:835:void node::RealPath(const v8::FunctionCallbackInfo<v8::Value>&): Assertion `(args.Length()) >= (2)' failed.
 1: node::Abort() [node]
 2: node::Assert(char const* const (*) [4]) [node]
 3: 0x56266a36ed3d [node]
 4: v8::internal::FunctionCallbackArguments::Call(void (*)(v8::FunctionCallbackInfo<v8::Value> const&)) [node]
 5: 0x562669c992df [node]
 6: 0x562669c9982f [node]
 7: 0x1502096842fd
Aborted (core dumped)
```
