# *I have 3 assignments due this weekend and I feel stressful so I find the original crying meme*
### **Then put a sentence to this meme and save it as a png file**

<!--- unordered lists --->
* library(magick)

* meme <- image_read("https://i.kym-cdn.com/photos/images/original/001/111/566/cf0.jpg") %>% 

<!--- numbered lists --->
 1. image_annotate(text = "Me when all the assignments due this weekend",
                        color = "#C70404",
                        size = 30,
                        font = "Impact")

2. image_write(meme, "my_meme.png")
