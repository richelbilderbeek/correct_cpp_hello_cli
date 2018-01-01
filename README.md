# correct_cpp_hello_cli

[Correct C++](https://github.com/richelbilderbeek/correct_cpp) chapter 'Hello CLI'.

## Exercise

Write a command-line interface (CLI) program that writes `Hello` to the screen.
If the user has supplied a command-line argument, show it, after adding a space between 'Hello' and the argument.
Ignore command-line arguments beyond the first.
In all cases, the output should be followed by a newline:

Call to `hello_cli`|Result
---|---
`./hello_cli`|`Hello` (with newline)
`./hello_cli world`|`Hello world` (with newline)
`./hello_cli world i_am_ignored`|`Hello world` (with newline)

This is the code you start with:

```c++
main(argc, argv)
{
  //Your code here
}
```

## Advice

 * Avoid `std::endl` [1]

## External links

 * [Richel Bilderbeek's page about argv](https://github.com/richelbilderbeek/cpp/blob/master/content/CppArgv.md)
 * [Qt Creator project file used in testing](https://raw.githubusercontent.com/richelbilderbeek/correct_cpp/master/hello_cli/main.pro)

## References

 * [1] [C++ Core Guidelines: SL.io.50: Avoid endl](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md#Rio-endl)



