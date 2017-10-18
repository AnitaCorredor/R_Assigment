###Anita Corredor R Assignment Review

## Loading Data
In line 11, I install the package "reader", since I didn't have that installed on my computer.

## Data Processing

I went to create a folder called what I thought would be called ***r_assignment*** on computer and load the files into, but ran into issues, because you created a folder called ***r_assigment***. Please run a spell checker through the assignment and check spelling.

In line 108 and line 115, got an message NAs introduced by coercion and invalid factor level.
I would revisit this section of code and look for ways to not produce these error messages. 

In line 130 and line 136, got an message NAs introduced by coercion and invalid factor level.
I would revisit this section of code and look for ways to not produce these error messages. 

In line 151 and line 157, got an message NAs introduced by coercion and invalid factor level.
I would revisit this section of code and look for ways to not produce these error messages. 

In line 172 and line 178, got an message NAs introduced by coercion and invalid factor level.
I would revisit this section of code and look for ways to not produce these error messages. 

It didn't create the correct files, due to not replacing the missing data correctly. 

Also what about removing snps with multiple or unknown chromosome positions. 

##Visualization

The visualization part was great seems that you did a really great job on that part.

##Overall

I would highly recommend using a spell checker because there is multiple spelling errors in text. I would figure out how replace the missing data correctly.

Here is some code from my assignment that should fix that.

incr_maize <- as.matrix(incr_maize)
incr_maize[incr_maize=="?/?"]<-"?"
incr_maize <- as.data.frame(incr_maize)