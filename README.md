XML Reader to CSV Converter

This project is a simple XML reader and converter that allows users to select a folder and read all XML files within that folder. The tool then creates a CSV (Excel-compatible) file containing either CNPJ, CPF, or both along with the respective entity names (company names or individuals' names). Users can choose the search criteria (CPF, CNPJ, or both) for extraction.

Features
XML File Parsing: The program parses XML files present in the selected folder.
Search by CPF, CNPJ, or Both: Users can choose whether to extract data based on CPF, CNPJ, or both.
CSV File Creation: The extracted data is saved to a CSV file, making it easy to view and analyze in Excel.

How to Use
git clone https://github.com/Gabriel-Inoveh/Leitor-de-XML.git

Install Dependencies:
pip install -r requirements.txt

Run the Program:
python main.py

Select a Folder:
Choose the folder containing the XML files you want to process.

Select Search Criteria:
Choose whether you want to search by CPF, CNPJ, or both.

Run Conversion:
Run the conversion process to generate the CSV file with the desired data.

Support and Contribution
For any issues or feature requests, please open an issue on the GitHub repository.
Feel free to fork the repository and submit pull requests to contribute to this project. We welcome contributions!
