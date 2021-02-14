# NZ motor vehicle register - make and model data cleansing code

Our Motor Vehicle Register (MVR) open dataset contains information on vehicle make and models, as well as other information. 

[MVR open data (NZTA open data portal)](https://opendata-nzta.opendata.arcgis.com/search?tags=MVR) 

The open dataset isn’t the original raw data, as sometimes make and model information is misspelled when people fill in forms with vehicle details. 

Instead, we clean the dataset and release the result, with repaired make and model spellings. This improves the quality of the dataset, and allows better and more accurate analysis.

This cleansing script is what we use to clean the data.

We’ll publish any updates to our internal codebase, here as well.

Note: the cleansing script is used to correct identified errors (such as spelling mistakes and other free text field inputs subject to human error) in vehicle makes and model fields in Motor Vehicle Register.

If you have any questions or comments about this code, or suggestions for how to improve it, please let us know at [statisticalanalysis@nzta.govt.nz](mailto:statisticalanalysis@nzta.govt.nz). 
We’d also love to hear about any uses you put it to.

## Prerequisites

The script is written in the coding language R. To use it, add the code into any software that can run R.<br/>
[What is R? (R project)](https://www.r-project.org/about.html)

## Authors

New Zealand Transport Agency - Specialist Analytics team

## License

This project is licensed under the MIT Licence - see the [LICENCE.md](LICENCE.md) file for details.

## Tags

#opendata, #vehicles, #cars, #opensource
