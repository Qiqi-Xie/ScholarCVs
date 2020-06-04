## My pagedown rendered CV

This repo contains the source-code and results of my CV built with the [pagedown package](https://pagedown.rbind.io). 

The main files are:

- `index.Rmd`: Source template for the cv, contains a variable `PDF_EXPORT` in the header that changes styles for pdf vs html. 
- `index.html`: The final output of the template when the header variable `PDF_EXPORT` is set to `FALSE`.
- `Qiqi Xie’s CV.pdf`: The final exported pdf. 
- `positions.csv`: A csv with columns encoding the various fields needed for a position entry in the CV. A column `section` is also available so different sections know which rows to use.
- `profile.json` and `citation.json`: Citation stats from Google Scholar queried by [scholar](https://cran.r-project.org/package=scholar) package.
- `citation.R`: Source code to generated `profile.json` and `citation.json`, as well as citation trend figure, `citation.png`.

参考资料：[datadrivencv包官方说明](http://nickstrayer.me/datadrivencv/)

[nstrayer/datadrivencv](https://github.com/nstrayer/datadrivencv)

[GuangchuangYu/cv](https://github.com/GuangchuangYu/cv)

[质感满满的简历，你也可以有！](https://mp.weixin.qq.com/s/Dz2fa83O_P5QPD8VLR7DRQ)

[怎样使用R语言制作一份高大上的简历](https://www.jianshu.com/p/6739af01d594)

[Pandoc官网](https://pandoc.org/installing.html#macos)
