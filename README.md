# IronKit

Add Python support to your red-team tools using **IronPython**, but without any dependencies (IronPython DLLs or **Python** installation).

# Introduction

This repository contains a class library of merged code of IronPython DLLs: IronPython, IronPython.Modules, Microsoft.Scripting, Microsoft.Dynamic and Microsoft.Scripting.Metadata. The purpose was to use IronPython without any DLL dependencies for Red team assessments and without Python installation.

# Release Notes

-   This is the initial version, built with .NET 4.5 and Visual Studio 2019
-   Use the code by adding it to your project, or simply add your code to IronKit project and change the project type (target) of the project (for example, from class library to program).

# Demo with Zolom

This repository contains a modified version of [Zolom](https://github.com/checkymander/Zolom) created by [@checkymander](https://github.com/checkymander). Zolom is an Executable created using C# and uses IronPython to run python code on systems without installing Python. The version of Zolom in this repository was modified to use IronKit instead of IronPython DLLs and dependencies (IronPython.dll, IronPython.Modules.dll, Microsoft.Dynamic.dll and Microsoft.Scripting.dll).

# License

```
Copyright 2018 Nader Shallabi. All rights reserved. 

IRONKIT CAN BE COPIED AND/OR DISTRIBUTED WITHOUT ANY EXPRESS PERMISSION OF NADER SHALLABI.

THIS SOFTWARE IS PROVIDED BY NADER SHALLABI ''AS IS'' AND ANY EXPRESS OR IMPLIED
WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND
FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL NADER SHALLABI
OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS
OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED
AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF
ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

The views and conclusions contained in the software and documentation are those of the authors and
should not be interpreted as representing official policies, either expressed or implied, of Nader Shallabi.
```
