# IPC

[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/Microsoft/IPC/blob/master/LICENSE) [![Build status](https://ci.appveyor.com/api/projects/status/dl929xf6rgaj257b/branch/master?svg=true)](https://ci.appveyor.com/project/ara-ayvazyan/ipc/branch/master)

IPC is a C++ library that provides inter-process communication using shared memory on Windows.<br/>
A .NET wrapper is available which allows interaction with C++ as well.

Integration with [Bond](https://github.com/Microsoft/bond) is available at [IPC.Bond](https://github.com/Microsoft/IPC.Bond).

# Build

The library is developed and maintained with [Visual Studio 2015](https://msdn.microsoft.com/en-us/library/dd831853.aspx).
To get started, open the [IPC.sln](https://github.com/Microsoft/IPC/blob/master/IPC.sln) file and build the solution.
The [Boost package](https://www.nuget.org/packages/boost/) will automatically start downloading during the first build.

# Getting Started

Start with [C++](https://github.com/Microsoft/IPC/blob/master/UnitTests/TransportTests.cpp) and [C#](https://github.com/Microsoft/IPC/blob/master/UnitTestsManaged/TransportTests.cs) tests.

# Contributing

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

# License

Copyright (c) Microsoft Corporation. All rights reserved.

Licensed under the [MIT](https://github.com/Microsoft/IPC/blob/master/LICENSE) License.
