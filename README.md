# -This is a problem when I practising using the operator in C++， which is the << overloaded function.

I meet the problem when I returning the ostream& out. The problem says “Try to refer to a deleted function or an explicit deletion function”, after searching the Baidu, I find that I forget a "&" before the "operator<<".


And maybe the "cout <<" can only output the basic type of elements. When you have other usage, please overload it.
