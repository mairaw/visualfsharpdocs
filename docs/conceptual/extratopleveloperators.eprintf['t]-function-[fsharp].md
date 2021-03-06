---
title: ExtraTopLevelOperators.eprintf<'T> Function (F#)
description: ExtraTopLevelOperators.eprintf<'T> Function (F#)
keywords: visual f#, f#, functional programming
author: dend
manager: danielfe
ms.date: 05/16/2016
ms.topic: language-reference
ms.prod: visual-studio-dev14
ms.assetid: e6cc9bc9-eb95-44b0-9551-0a7f02dca17c 
---

# ExtraTopLevelOperators.eprintf<'T> Function (F#)

Print to **stderr** using the given format.

**Namespace/Module Path**: Microsoft.FSharp.Core.ExtraTopLevelOperators

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## Syntax

```
// Signature:
eprintf : TextWriterFormat<'T> -> 'T

// Usage:
eprintf format
```

#### Parameters
*format*
Type: [TextWriterFormat](https://msdn.microsoft.com/library/2080c4a5-7bdd-4a01-8e01-10b498af92de)**&lt;'T&gt;**




## Remarks
This function is named **PrintFormatToError** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.

**The following code example demonstrates the use of eprintf.**
[!code-fsharp[Main](snippets/fscorelib2/snippet2.fs)]
**The output is as follows.**
**Success!**
**Error: the input 11 exceeds the maximum value 10.**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0




## See Also
[Core.ExtraTopLevelOperators Module &#40;F&#35;&#41;](Core.ExtraTopLevelOperators-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core-Namespace-%5BFSharp%5D.md)

