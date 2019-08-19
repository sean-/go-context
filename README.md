### go-context - jbenet's CONText EXTensions

https://godoc.org/github.com/sean-/go-context

- `WithDeadlineFraction`: https://godoc.org/github.com/sean-/go-context/ext#WithDeadlineFraction
- `WithParents`: https://godoc.org/github.com/sean-/go-context/ext#WithParents
- `io.{Reader, Writer}`: https://godoc.org/github.com/sean-/go-context/io


# Background

This is a hard fork
of [`jbenet/go-context`](https://github.com/jbenet/go-context) with context
improvements.  This repo was discovered while looking through
https://github.com/golang/go/issues/20280 and looking for an existing
implementation of an `io.Reader`/`io.Writer` wrapper that used a
`context.Context`.
