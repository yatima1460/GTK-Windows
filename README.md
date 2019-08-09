# GTK3 binaries built for Windows x86_64

Binaries built using [vcpkg](https://github.com/microsoft/vcpkg) on Windows.

|VS 2015|VS 2017|VS 2019|
|------|------|------|
|![](https://dev.azure.com/yatima1460/GTK3-Windows-x64/_apis/build/status/yatima1460.GTK3-Windows-x64?branchName=master&jobName=GTK%20x86_64%20VS2015)|![](https://dev.azure.com/yatima1460/GTK3-Windows-x64/_apis/build/status/yatima1460.GTK3-Windows-x64?branchName=master&jobName=GTK%20x86_64%20VS2017)|![](https://dev.azure.com/yatima1460/GTK3-Windows-x64/_apis/build/status/yatima1460.GTK3-Windows-x64?branchName=master&jobName=GTK%20x86_64%20VS2019)|

|Publish|
|------|
|![](https://dev.azure.com/yatima1460/GTK3-Windows-x64/_apis/build/status/yatima1460.GTK3-Windows-x64?branchName=master&jobName=Publish)|


# F.A.Q.

- Where are the binaries and include files?
  - Open/Extract the archive
  - `installed\x64-windows`
- Which version of GTK? 
  - `vcpkg` always builds the latest GTK version
- Where can I find the version?
  - Open/Extract the archive
  - `installed\vcpkg\info`
- Why not x86 (32-bit)?
  - It's almost 2020 when I'm writing this, c'mon
- How to use it with CMAKE?
  - Open/Extract the archive
  - `-DCMAKE_TOOLCHAIN_FILE=GTK_x86_64_VS20XX/scripts/buildsystems/vcpkg.cmake`

# License

GPL-2.0 is obviously applied only for this repository, not what it builds
