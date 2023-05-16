

# Introduction
  

This repository contains code and data for my article "[Satellite Data Analysis with Google Earth Engine and Graph Databases](https://dgg32.medium.com/satellite-data-analysis-with-google-earth-engine-and-graph-databases-193ad56c0d2f)".

1. The notebooks are for data acquisitions, formatting and import.

2. The CSV data in raw_data are downloaded from ekidata.jp. The data in import_ready_data are ready for import into Memgraph or Gemini Explore
  

# Prerequisite

Memgraph

Gemini Cloud account

Google Earth Engine Account
  

# Run
1. run private_fastapi_gee.ipynb to start your own GEE API in ngrok
  
2. run Eki_Japan.ipynb in your Google Colab to process the data 

3. Import the data into Memgraph following the instructions in memgraph_command.txt

4. Import the data into Gemini Explore following the instructions in my article



## Authors

  

*  **Sixing Huang** - *Concept and Coding*

  

## License

  

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
