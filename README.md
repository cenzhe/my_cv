# My Resume

This work is written in markdown. [markdown-resume](https://github.com/there4/markdown-resume) is used to convert it into html/pdf.

`md2resume` is the output binary from *markdown-resume*. Put it in `$PATH`, and run the following with php runtime.

``` shell
md2resume html -t swissen cenzhe_cv.md ./
md2resume pdf -t swissen cenzhe_cv.md ./
```
