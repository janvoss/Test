# Test

Dies ist ein Test. Ein Test. 

library(owidR)

# Data Smoking

# Data Lifestyle expectancy

# DataGdp per c

# left join

# Figure

df %>% ggplot(aes(smoking, expectancy))+
geom_point()+
geom_smooth()

df %>% ggplot(aes(smoking, gdp_pc))+
geom_point()+
geom_smooth()


df %>% ggplot(aes(gdp_pc, expectancy))+
geom_point()+
geom_smooth()



