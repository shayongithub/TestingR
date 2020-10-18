add2 <- function(x, y){
x +y
}
big10 <- function(c) {
  ans <- c()
  for (i in c) {
    if ( i > 10 ){
      ans <- append(ans, i)
    }
  }
  ans
}

above_num <- function(c, n) {
  c[c>n]
}

column_mean <- function(data, removeNA = TRUE) {
  ans <- c()
  for (i in seq_len(ncol(data))) {
    ans <- append(ans, mean(data[[i]], na.rm = removeNA))
  }
  ans
}