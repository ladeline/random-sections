# random-sections

**Random Sections**  randomly splits an array into random sections of a specific length

The outputs are :
 
- Sections.csv file  - a csv file where each row will be x length long  (or x+1 long if there is a remainder)
- output/ folder with Sections_#.pdf files - Input a  pdf file, and it will split the pdf into sections x (or x+1) pages long

## Installation

This application is a Jupyter notebook , so run a Jupyter Kernel in order to use.


## Usage

Inputs should be outlined in the Jupyter Notebook.

-Run the first cell if your Jupyter Kernel doesn't have the listed packages installed (numpy,pandas,PyPdf2)
-Run the **Array Split** cells in order to get the array randomized and split into sections
-To run the **PDF Split** cells : first run the **Array Split** cells , then run **PDF Split**

## Contributing
Pull requests are welcome. Open an issue if there are any comments or requests.

## License
[MIT](https://choosealicense.com/licenses/mit/)
