# WebAssembly Debugging Subgroup Charter

The Debugging Subgroup is a sub-organization of the
[WebAssembly Community Group](https://www.w3.org/community/webassembly/) of the W3C.
As such, it is intended that its charter align with that of the CG. In particular, 
the sections of the CG charter relating to Community and Business Group Process,
Contribution Mechanics, Transparency, and Decision Process also apply to the Subgroup.

## Goals

The mission of this sugbroup is to provide a forum for pre-standardization
collaboration on debugging capabilities for WebAssembly programs.

## Scope

The Subgroup will consider topics related to debugging, profiling, or
static analysis of WebAssembly programs, including:

- File formats and encodings for WebAssembly debug information
e.g. as custom sections in wasm executables or object files, 
- Extensions to the WebAssembly text format for debug information
- Extensions or modifications to
- Interaction with browsers (e.g. developer tools, debugging, profiling)
- Interaction with external debuggers and IDEs (VS Code), and
debuggers running in the browser
- Presentation of source, callstack, or debugging information in browsers, debuggers,
or IDEs


## Deliverables

### Specifications
The Subgroup may produce several kinds of specification-related work output:
- Extensions or amendments to existing specifications (e.g. Wasm core or
web spec, DWARF, EcmaScript)
- Creation of new specifications in standards bodies or working
groups (e.g. Wasm WG or TC39)
- Creation of new specifications outside of standards bodies
(e.g. similar to LLVM object file format in Wasm tool conventions)

### Non-normative reports
The Subgroup may produce non-normative material such as requirements
documents, recommendations, and use cases.

### Software
The Subgroup may produce software related to Wasm debugging (either as
standalone tooling or integration of debugging related functionality
in existing CG software such as Binaryen or WABT). Capabilities may include:
- Debug info encoding or translation
- Program instrumentation or analysis
- Interactive debuggers or profilers
- Test suites

## Amendments to this Charter and Chair Selection

This charter may be amended, and Subgroup Chairs may be selected by vote of the full
WebAssembly Community Group.
