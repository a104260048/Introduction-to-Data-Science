用Rmarkdown可寫碩士論文、學期報告、統計計量作業、投稿學術期刊等等特殊格式的文章。

- 請參考網址[Templates for R Markdown](http://jianghao.wang/post/2017-12-08-rmarkdown-templates/)。
- 如何做靜態網頁與部落格
  - [靜態網頁參考：Rmarkdown Website](https://livefreeordichotomize.com/2017/08/08/how-to-make-an-rmarkdown-website/)
  - [部落格參考：Rmarkdown Blogs](https://livefreeordichotomize.com/2017/07/13/introducing-the-tuftesque-blogdown-theme/)
- 請安裝Rticles, tufte套件，直接在Rstudio上修改，頗為方便好用。
  - [Rticles套件](https://github.com/rstudio/rticles)

```
#以ritcles為例，可直接用菜單安裝
#從R官網安裝
install.packages("rticles")
#從Github上安裝
devtools::install_github("rstudio/rticles")
```

**作業練習**

將Rstudio中Rmarkdown的文件範例，改為下面的Rmarkdown作業格式輸出。 <https://github.com/alexpghayes/rmarkdown_homework_template>

答案關鍵在範例程式的最後面，亦即加上下面指令即可：

# Code

```{r ref.label = knitr::all_labels(), echo = TRUE, eval = FALSE}
# this R markdown chunk generates a code appendix
```
