---
layout: post
title:      "Difference between var and let scope"
date:       2020-05-06 20:46:21 +0000
permalink:  difference_between_var_and_let_scope
---


These two variable declariations are like siblings.  There is a difference between the two that makes one more preferable than the other depending on what it is you are using them for.  The "var" declariations are considered to be function scoped. Function scoped means that it can be accessed anywhere in that function.  The "let" declaration on the other hand is considered to be blocked scoped.  Blocked scoped means that it can only be accessed within the block that it's declared in and no accessable anywhere outside of its {}. A "var" variable declared inside of a block can still be accessed outside of that block.  Hoisting is what happens in the complilation phase where all the variables and functions get moved to the top of their scope before the execution phase. So in all actuality, all variables and functions get hoisted.  Since "var" are declared in the entire scope it gets initialized as undifened the declarations gets iniatlized in that scope while let remains unintialized if called before its intialized in the scope.
