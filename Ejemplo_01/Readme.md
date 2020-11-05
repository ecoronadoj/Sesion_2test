 # ESte es el ejemplo 1
#### código 1

´´´ R
mean(xml_df$PRICE)
mean(xml_df$YEAR)
´´´
#### código 2
´´´R
# Más fácil
url3 <- URL2 # cargué el URL del XML
 data_df <- xmlToDataFrame(url3)
´´´
