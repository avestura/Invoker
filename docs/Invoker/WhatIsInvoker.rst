What is Invoker?
=================

Invoker is an online documentation of P/Invoke (Platform Invoke) of Windows API. In Invoker_ ,
you can use, add or remove the P/Invoke signatures, structures, types or any useful information 
for your project or for your knowledge that is related to calling Win32 unmanaged APIs from managed 
code (.NET languages).

What is managed and unmanaged code?
-------------------------------------

C# programs run on the .NET Framework, an integral component of Windows that includes a virtual 
execution system called the common language runtime (CLR) and a unified set of class libraries.
Code that is executed by the CLR is sometimes referred to as "managed code," in contrast to "unmanaged code"
which is compiled into native machine language that targets a specific system.

Related topics from Microsoft Documentations
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
* `What is a managed code?`_
* `extern Modifier (C# Reference)`_
* `Interop Marshaling`_
* `Marshal Class (System.Runtime.InteropServices)`_

Useful Resources
-----------------

* `AArnot pinvoke`_ A library containing all P/Invoke code so you don't have to import it every time. Maintained and updated to support the latest Windows OS. 
* `PInvoke.Net VS Extension`_  Access PInvoke.net directly from within Visual Studio


Contribution
=============

Contributions are very welcome in Invoker. You can edit, add or remove docs and make them
better in the way you think. Simply use *Edit on Github* option in top of any page.


.. _Invoker: https://platform-invoker.readthedocs.io/en/latest/Invoker/WhatIsInvoker.html
.. _AArnot pinvoke: https://github.com/AArnott/pinvoke
.. _PInvoke.Net VS Extension: https://marketplace.visualstudio.com/items?itemName=vs-publisher-306627.PInvokenetVisualStudioExtension
.. _What is a managed code?: https://docs.microsoft.com/en-us/dotnet/standard/managed-code
.. _extern Modifier (C# Reference): https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/extern
.. _Interop Marshaling: https://docs.microsoft.com/en-us/dotnet/framework/interop/interop-marshaling
.. _Marshal Class (System.Runtime.InteropServices): https://docs.microsoft.com/en-us/dotnet/api/system.runtime.interopservices.marshal?view=netframework-4.7.1