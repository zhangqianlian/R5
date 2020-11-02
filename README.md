# R5
第五节R语言练习2002070008张倩莲新医科

#5——1
a_list <- list(
  matrix(c(1,4,9),nrow = 1),
  c(16),
  c(25),
  c(36),
  c(49),
  NA,
  c(64),
  NA,
  c(81),
  NA
   )
names(a_list) <- c("n1","n2","n3","n4","n5","n6","n7","n8","n9","n10")
a_list


#5——2
a_data_frame <- data.frame(
  Sepal.Length = iris[1:150,1],
  Sepal.Width = iris[1:150,2],
  Petal.Length = iris[1:150,3],
  Petal.Width = iris[1:150,4]
)
mean(iris[1:150,1])
mean(iris[1:150,2])
mean(iris[1:150,3])
mean(iris[1:150,4])


#5——3
b1_data_frame <- data.frame(
  id = 1,
  beaver1
)
b1_data_frame

b2_data_frame <- data.frame(
  id = 2,
  beaver2
)
b2_data_frame

B_data_frame <- rbind(b1_data_frame , b2_data_frame)#垂直拼接两个数据框

subset(B_data_frame,activ="1")


