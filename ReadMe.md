1) All the chapters contains standalone code i.e Any code snippet in the chapters would work if copy pasted from the chapters directly to the Julia REPL

2)This Code Bundle include .jl files of all the functions which can be compiled in the JUlia REPL 
 To compile the .jl function use
include("path:\\file_name.jl")

3)Some code files contains function with similar names, to avoid compilation errors use workspace() to replace the top-level module (Main) with a new one, providing a clean workspace. The previous Main module is made available as LastMain. A previously-loaded package can be accessed using a statement such as using LastMain.Package.

4) To precompile packages use keyword, using package_name
