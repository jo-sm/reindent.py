# reindent.py

`reindent.py` with option to change the number of spaces.

This implementation adds the [patch for multiline string literals by Roger Serwy](https://bugs.python.org/issue12930#msg171678) and adds an `--indent` option that allows for non-4 space width indentations.

## Note

Originally this was committed on August 11, 2016, but I realized the patch and the `--indent` flag were not added as separate commits. I separated out the code changes into three commits, so now the original `reindent.py`, the patch, and my `--indent` flag are separate in the history.

## Usage

```
> reindent.py --indent=2 ./myfile.py
```

## License

Original code and patch, [PSF](LICENSE-PSF.txt)

Changes, [MIT](LICENSE-MIT.txt)
