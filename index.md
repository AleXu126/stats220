library(magick)
# I have 3 assignments due this weekend
meme <- image_read("https://i.kym-cdn.com/photos/images/original/001/111/566/cf0.jpg")%>% 
# Put a sentence to match this meme  
  image_annotate(text = "Me when all the assignments due this weekend",
                        color = "#C70404",
                        size = 30,
                        font = "Impact")
image_write(meme, "my_meme.png")
