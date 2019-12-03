# DeterministicExample

Steps to reproduce:

1) Clone the repository to two different locations
2) Run `xcodegen generate` in both directories
3) Diff the generated DeterministicExample.xcodeproj files in both projects --> They are identical
4) Run `pod install` in both projects
5) Diff the xcodeproj again --> They are not the same anymore


* xcodegen: https://github.com/yonaskolb/XcodeGen
* cocoapods: https://cocoapods.org
