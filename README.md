# tk

Tk (Tcl/Tk 8.6+, preferring 9.1) backend for the hikap hiccup engine: the
classic `:tk/…` and themed `:ttk/…` widget tag sets, the host FFI Tcl adapter,
and the sample `:ui/transcript` widget.

Package reference: [src/kmet/tk/README.md](src/kmet/tk/README.md).

## Tests

    bb test
    jolt test

The JVM suite uses `clojure -M:test`; the test alias adds the standalone FFI.

## License

Copyright © 2026 — present Marko Kocic <marko@euptera.com>

Licensed under the Eclipse Public License 2.0 ([EPL-2.0](LICENSE)).
