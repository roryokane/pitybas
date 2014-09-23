pitybas
=======
A working TI-BASIC interpreter, written in Python.

Currently, all `.bas` files in [tests/](https://github.com/lunixbochs/pitybas/tree/master/tests) run except [circle.bas](https://github.com/lunixbochs/pitybas/blob/master/tests/circle.bas) (due to lack of graph screen functions).

Use `pb.py -i vt100` to run programs which need a working home screen.

If you run `pb.py` with no filename, it launches an interactive shell.

	Usage: pb.py [options] [filename]

	Options:
		-h, --help        show this help message and exit
        -a, --ast         parse, print ast, and quit
		-d, --dump        dump variables in stacktrace
		-s, --stacktrace  always stacktrace
		-v, --verbose     verbose output
		-i IO, --io=IO    select an IO system: simple (default), vt100

