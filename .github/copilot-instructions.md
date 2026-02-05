# VAD-tools Codebase Instructions

## Project Overview
MATLAB toolbox for plotting and general utility.

## Development Guidelines

### Function Style
- Use MATLAB `arguments` blocks for input validation
- Include H1 line (one-line description) for all functions
- Add short comments to each function argument on a separate line above the declaration:
  ```function function_name(arg1, arg2, ...)
  %%% Brief 1-3 line description of the function's purpose.
  arguments
      % Description of the argument
      arg1 (1, 1) double
      [blank space before next argument]
      % Description of the next argument
      ...
  end
  ```

### Naming
- Functions use `snake_case`
- Variables use `snake_case`
