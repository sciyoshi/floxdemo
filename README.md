This sample is mostly based off of [this sample repository](https://github.com/flox/floxenvs/tree/main/python-uv).

**Issues**

* On Linux, `uv` does not work correctly due to [this known issue](https://github.com/flox/flox/issues/1341). Unsetting LD_AUDIT fixes it.
* On Linux, running `python hello.py` will error with [this issue](https://nixos.wiki/wiki/Packaging/Quirks_and_Caveats#ImportError:_libstdc.2B.2B.so.6:_cannot_open_shared_object_file:_No_such_file).
