# Random Stuff
Random and obscure code that may be helpful to others

The purpose of this repo is just to house ad hoc code I write normally for some very inane reason. This repo wont be maintained but if something in it saves you five minutes then happy to help.

Contents
1. Understand foreign exchnage Danske Bank PDF statements and converting into DataFrame
   - after spending many hours playing with tabula py and pdfquery and so on, its easier to use adobe to merge pdfs and export as xlsx or csv. if data is tabula then tabulapy is great
   - then import into pd dataframe
   - calculate total of flat fees stated within the pdfs
   - calculate the forex spread the bank is charging you (which they do not show on the statments) and sum
   - includes a double check
   - Dependencies: pandas, GoogleTranslator (free api).
