![icon2](https://github.com/user-attachments/assets/ff6187fb-3c87-4f5c-a439-500d85240ace)
# Y Programming Language
Y is an interpreted dynamic programming language.
# Types
- dyn (Dynamic)
- int
- float
- bool
- str
- list
# Variable
var NAME ///TYPE is dyn by default
var TYPE NAME
var TYPE NAME = VALUE
NAME = VALUE
# Function
func NAME
  ACTION_S
end

func NAME
  rec RECEIVEDVALUE_S
  ACTION_S
end

func TYPE NAME
  ACTION_S
  ret RETURNEDVALUE
end

func TYPE NAME
  rec RECEIVEDVALUE_S
  ACTION_S
  ret RETURNEDVALUE
end

func NAME ACTION_S end
# Class
class NAME
end
