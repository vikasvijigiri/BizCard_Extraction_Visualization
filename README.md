# **Aim**
To extract text from business card image(s), store it in the MySQL local server, and display extracted data using pandas.

## **Data Collection**
The data is collected from a [Google Drive source](https://drive.google.com/drive/folders/1FhLOdeeQ4Bfz48JAfHrU_VXvNTRgajhp) with five+ business card templates.

## **Data Categorization**
The textual data typically includes information such as:
- **'Name of the business/person'**
- **'Designation'** 
- **'Phone numbers'** 
- **'Email Id'** 
- **'Website'**
- **'Address'** 

## Prerequisites
Run the following command to install all required packages.
- To run:
  ```bash
  pip install -r requirements.txt

After extraction, the UI provides an option to either save or discard the data in the MySQL database server.

## **Supported Images**
The current version of the BizCard reader is compatible with images of the following extensions in formats:
- **'JPEG/JPG'**
- **'PNG'** 

## **Features**
- **Introduction**: App characteristics
- **Extraction**: From Drive
- **Data Management**: Migration of the extracted data to MySQL (SQL)
- **Data Visualization**: Pandas

## **USAGE**
- To run the Streamlit application, execute the following command in your terminal:
  ```bash
  streamlit run streamlit_app.py

## **Feedback**
Please feel free to explore. Feedback is most welcome. For any comments, questions, or queries, contact the UI developer **[Vikas](mailto:vikki.4me@gmail.com)**. Thank you!
