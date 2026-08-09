# compilers.errors

Language-agnostic compiler exceptions shared across the `compilers`
namespace (e.g. `compilers.C`).

Exposes the base `Error` and its general subclasses (`UnknownFileType`,
`PlatformError`) so that any `compilers.<lang>` distribution and its
consumers can raise and catch compiler errors without depending on a
particular compiler implementation.
