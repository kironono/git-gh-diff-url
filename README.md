# git-gh-diff-url

NAME
----
git-gh-diff-url - generate github refs diff url (github.com/user/repo/compare/...).

---

<img width="1486" alt="image" src="https://user-images.githubusercontent.com/1598505/132937087-f5511488-6744-4783-8d6f-0e955a6189f5.png">


USAGE
----
```
 * git-gh-diff-url --left [LEFT] --right [RIGHT] [OPTIONS]
 *  [-l|--left]  [hash|tag|branch]     # Left side git ref used for compare. (default: remote oring default branch)
 *  [-r|--right] [hash|tag|branch]     # Right side git ref used for compare. (default: current branch)
 *  [-o|--refs-mode] [r|l|lr]          # Specify url ref hash mode. r or l or lr or rl(default: l)
 *  [-v|--verbose]                     # Verbose mode.
 *  [-s|--simple]                      # Simple output mode.
 *  [-b|--browser]                     # open create url to GIT_GH_DIFF_URL_BROWSER cmd.
 *  [-t|--output] [text|html|markdown] # Specify output text type. (default: markdown)
```

ENVIRONMENTS
----
```
GIT_GH_DIFF_URL_BROWSER_DARWIN           # Browser command to be used if you are on MacOSX. (default: use chrome)
GIT_GH_DIFF_URL_BROWSER_LINUX            # Browser command to be used if you are on Linux. (default: use chrome)
GIT_GH_DIFF_URL_BROWSER                  # Highest priority browser command.
GIT_GH_DIFF_URL_DEFAULT_REFS_MODE        # Default use `--refs-mode` option. (default: "l")
GIT_GH_DIFF_URL_DEFAULT_OUTPUT_TEXT_TYPE # Default use `--output` option. (default: "markdown")
```


MIT License

Copyright (c) 2021 Hiroshi IKEGAMI

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
