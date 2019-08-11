# TS2596 24V to 5V@3A regulator
This design is a simple breakout card for the TS2596 buck 40V Vin to 5V @ 3A Vout regulator. 
Main reason was to supply a 5V USB socket for a web cam off the 24V supply in my Prusa 3d printer. 

License is MIT so do what you want with it just don't litigate me. 

## KiCad
This is a KiCad 5.1.0 project. 

Gerber data and spreadsheet of the bill of materials can be found in here. 


## OSHpark PCBs
V0 PCB design can be found here:
https://oshpark.com/shared_projects/jKUSeUO9

V1 just added polarity marks to the back silk screen (Square pad is positive) 


## Build notes
I just used a iron to assemble most of the cards starting with the smallest component and worked my way up. 
The regulator thermal pad was a pain. None of my irons could get it hot enough. Ended up using a hot air gun to heat the board and pad to solder them. 
If you have a reflow oven or skillet recomend using it for this part. Rest can be hand soldered with no issues. 


Copyright (c) 2019 Peter Shabino

Permission is hereby granted, free of charge, to any person obtaining a copy of this hardware, software, and associated documentation files 
(the "Product"), to deal in the Product without restriction, including without limitation the rights to use, copy, modify, merge, publish, 
distribute, sublicense, and/or sell copies of the Product, and to permit persons to whom the Product is furnished to do so, subject to the 
following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Product.

THE PRODUCT IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF 
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE 
FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION 
WITH THE PRODUCT OR THE USE OR OTHER DEALINGS IN THE PRODUCT.
