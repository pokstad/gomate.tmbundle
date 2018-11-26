# GoMate - A Textmate Bundle for Go Code

GoMate is a [TextMate](https://macromates.com) bundle for working with Go code.

GoMate borrows heavily from the [original Golang extension](https://github.com/syscrusher/golang.tmbundle).

GoMate adds functionality through a CLI tool called [gomate](https://github.com/pokstad/gomate) that wraps many functions for proper interoperability with TextMate.

## Installation

Execute the following commands on your Mac with TextMate 2.x and Go 1.11+ already installed:

```
git clone https://github.com/pokstad/gomate.tmbundle.git
open gomate.tmbundle
```

This will install the bundle to the following directory:

`~/Library/Application Support/TextMate/Pristine Copy/gomate.tmbundle`

Once TextMate finishes installing the bundle, run the bundle's command `install tools`.

And any changes to the bundle after installation will be stored in:

`~/Library/Application Support/TextMate/Bundles/gomate.tmbundle`
