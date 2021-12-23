# OCR
Optical Character Recognition

In this repo two methods are shown for extracting the data from image like 
1. By extracting the required portion of the image by using the Numpy. But it is useful when we have documents in the same format without any changes in the future.
2. Extracting the data from image using tesseract and opencv libraries

## Objective:

    - The main objective of this project is to extract the customer information from the monthly rechnung (bill).
    - Initially the "Pdf" is converted into the "Image" and then 'opencv' library is used for adjusting the color and thershold.
        + While converting the pdf to image. download and mention the 'Poppler' location
    - 'Tesseract' library is used for converting the image to string and data
        + download and mention the tesseract location
    - 'Regex' is utilized here for extracting the useful information like all details.
    - Then a dataframe is created for storing all details and further dataframe is stored as ".csv" file.
    - New Database connection is established for storing the .csv files and new tables are created for storing the image files
    - In this project postgresql database is used.
