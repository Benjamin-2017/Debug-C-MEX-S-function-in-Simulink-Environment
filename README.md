# Debug-C-MEX-S-function-in-Simulink-Environment
In MATLAB website,there is a document about Debug C MEX S-Functions
but for new user, a issue exists.
Debugging C MEX S-Functions Using the Microsoft Visual C++ .NET Environment
step 10 Set a breakpoint on the desired line of code by right-clicking on the line and selecting Insert Breakpoint from the context menu. If you have not previously run the model, the breakpoint may show up with a question mark, indicating that the executable is not loaded. Subsequently running the model loads the .mexw32 file and removes the question mark from the breakpoint.

it can be fixed by executing the following procedures:
(1) "clear mex"  in Matlab Command
(2) " Attach to Process" in VS debug menu bar
(3) set breakpoints 
(4) re-run SImulink MDL.
