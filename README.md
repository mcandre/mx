# mx: mage extras

[![API Docs](https://badgen.net/static/docs/API/007d9c?icon=go)](https://pkg.go.dev/github.com/mcandre/mx) [![CI/CD](https://badgen.net/github/checks/mcandre/mx?icon=github)](https://github.com/mcandre/mx/actions) [![License](https://badgen.net/static/license/BSD/ab2b29?icon=freebsd)](LICENSE.md) [![AI](https://badgen.net/static/人/NO%20AI?color=aa4a44)](AI-DECLARATION.md)

```text
  _ __ ___ __  __
 | '_ ` _ \\ \/ /
 | | | | | |>  <
 |_| |_| |_/_/\_\
```

# SUMMARY

mx streamlines common Go development tasks for projects built with mage.

# ABOUT

[API Docs](https://pkg.go.dev/github.com/mcandre/mx)

mx provides utility functions for common Go development operations.

Examples:

* `GoEnv` - Query the `go env` toolchain configuration subsystem
* `Install` - Compile and install Go executables
* Lint Go projects recursively:
  * `GoImports`
  * `GoVet`
  * `GoVetShadow`
  * `Nakedret`
* `UnitTest` - trigger unit test suite
* `NoVendor` - Query Go source file paths excluding vendoring
* `ExecSilent`, `RunVSilent` - Reduce command log noise

# PREREQUISITES

* [Go](https://go.dev/)
* [Mage](https://magefile.org/) 1.16.1+

For details on building from source, see [DEVELOPMENT](DEVELOPMENT.md).

# RESOURCES

Prior art and personal plugs.

* [invoke](https://pypi.org/project/invoke/) - 100% Python task runner
* [mage](https://magefile.org/) - 100% Go task runner
* [mcandre/tinyrick](https://github.com/mcandre/tinyrick) - 100% Rust task runner
* [mcandre/tuco](https://github.com/mcandre/tuco) - Go port multiplexer
* [Shake](https://shakebuild.com/) - 100% Haskell task runner

🐱
