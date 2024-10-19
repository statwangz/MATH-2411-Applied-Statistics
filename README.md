# Tutorials for MATH 2411 Applied Statistics

<!-- metrics -->
<p align="center">
    <a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fstatwangz%2FMATH-2411-Applied-Statistics&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false"/></a>
    <a href="https://github.com/statwangz/MATH-2411-Applied-Statistics/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/statwangz/MATH-2411-Applied-Statistics"></a>
    <a href="https://github.com/statwangz/MATH-4432-Statistical-Machine-Learning/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/statwangz/MATH-2411-Applied-Statistics"></a>
    <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/statwangz/MATH-2411-Applied-Statistics">
    <a href="https://github.com/statwangz/MATH-2411-Applied-Statistics/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/statwangz/MATH-2411-Applied-Statistics"></a>
    <a href="https://github.com/statwangz/MATH-2411-Applied-Statistics/issues?q=is%3Aissue+is%3Aclosed"><img alt="GitHub closed issues" src="https://img.shields.io/github/issues-closed/statwangz/MATH-2411-Applied-Statistics"></a>
</p>

## Course Information
 
Instructor: Dr. Jing Yao (<majyao@ust.hk>)

Teaching Assistant: Zhiwei Wang (<zhiwei.wang@connect.ust.hk>)

[HKUST Canvas link](https://canvas.ust.hk/courses/59569)

[Discord server](https://discord.gg/mAGzzwznQK) for discussions and Q&A.

## Tutorial Files

The source files of the slides are in `.Rmd` format.
You can have a look at them if you are interested in how to create slides through R Markdown.

To get a full view of the slides, I recommend opening the `.html` files (e.g., [`Introduction.html`](https://github.com/statwangz/MATH-2411-Applied-Statistics/blob/main/T01%20A%20Brief%20Introduction%20to%20R/Introduction.html)) with your browser after downloading the entire tutorial folder.
Typically this works best in Chrome.

I also provide the PDF version via John Paul Helveston and Garrick Aden-Buie's R package [**renderthis**](https://github.com/jhelvy/renderthis):
```r
renderthis::to_pdf(from = "filename.Rmd", complex_slides = TRUE, partial_slides = FALSE)
```
**However, the “complex” slides containing panelsets or other HTML widgets / advanced features might not render well as a PDF.**

## Acknowledgments

- Slides created via Yihui Xie's R package [**xaringan**](https://github.com/yihui/xaringan).

- Theme customized via Garrick Aden-Buie's R package [**xaringanthemer**](https://github.com/gadenbuie/xaringanthemer).

- Tabbed panels created via Garrick Aden-Buie's R package [**xaringanExtra**](https://github.com/gadenbuie/xaringanExtra/).