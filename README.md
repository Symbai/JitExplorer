# JitExplorer

Like [compiler explorer](https://godbolt.org/), but for .NET JIT.

![image](https://user-images.githubusercontent.com/12851828/86214260-cae3b880-bb2f-11ea-80b1-5c86e83ced64.png)

# TODO:

- Why is jitted code not release version? Is it related to roslyn compile?
- Async UI, progress bar
- Richer UI, pull down for x86/x64, debug/release, language version, platform, emit ass line nos, tiered compilation
- IsolatedJit Events/status for compile/jit/dissassemble, show in status bar
- Code auto complete, like RoslynPad


# References

https://github.com/aelij/RoslynPad
https://github.com/dotnet/BenchmarkDotNet/tree/master/src/BenchmarkDotNet.Disassembler.x64
