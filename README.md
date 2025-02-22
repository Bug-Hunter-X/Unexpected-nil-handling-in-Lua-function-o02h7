# Lua Nil Handling Bug

This repository demonstrates a subtle bug related to nil handling in a Lua function. The function `foo` is designed to return either `a`, `b`, or their sum, depending on whether the arguments are nil. However, the behavior is unexpected when both `a` and `b` are nil. 

The `bug.lua` file contains the buggy code. The `bugSolution.lua` file provides a corrected version. The issue is discussed in more detail below.  This example highlights the importance of carefully considering edge cases when dealing with nil values in Lua.