# Invisible Notice
<br>
:smile: This repository is a preparation for my personal website using Blogdown and RStudio. Thanks for every contributor in open-source community<br>
:sweat_smile: I will record something werid I encountered, but first I will try to fix these problems in my project. 

# can't insert image using Addins 'insert image'
written in 02/04/2023<br>
I find some out-of-date post about failure to insert images using blogdown, but all of them are released two or five years ago.<br>
Now Mine is the latest version of blogdown, but something strange is still there. :anguished:<br>
<br>
The detailed question can be seen in [stackoverflow](https://stackoverflow.com/questions/75343079/no-image-shown-after-inserting-image-using-blogdown-addins-insert-image-and-re)<br>
There is *a broken icon* in place of the inserted image on the rendered page.<br>
By the way, **every time I refresh the rendered page, it will trigger IDM to download the image I inserted just now**. That's really confusing.

# image will be copy to `\content\` rather than `static`
written in 02/04/2023<br>
[The blogdown tutorial](https://bookdown.org/yihui/blogdown/rstudio-ide.html) and [L. Collado-Torres](https://lcolladotor.github.io/2018/03/07/blogdown-insert-image-addin/#.Y94cjidByUk) shows that the image will be copied to `\static\` under root directory, **but in `blogdown 1.16` the image is not allowed to be save in '\statics\'.** Although the place where the image is saved doesn't matter, I don't know if this is the reason why the inserted image can't be shown well on rendered page.
