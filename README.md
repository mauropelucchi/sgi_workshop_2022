# SGI Workshop 2022

Workshop on Machine Learning in production for Statistics and Information Management course (2022)


In this repository you can find the materials from the Workshop 202 @ Data Mining course (STATISTICA E GESTIONE DELLE INFORMAZIONI - University of Milano Bicocca)

The workshop consists of two topics:

- Cloud Platform for Data Science: in this section we present Google Colaboratory and Databricks
- Big Data in a real project

In the first topic, the workshop presents a notebook (on Google Colab) about the use of Big Data Tools (Athena, PySpark, ...) to compute a similarity measure between occupations
with a dataset composed by 400M job postings (Thanks Simone Perego!!!). The notebook uses the RCA metric and different distance and similarity metrics.


In the second topic, the workshop presents a notebook (on Databricks) about the training of a basic Machine Learning model, that covers:

- Load of the data and ETL process
- Processing of the text (remove stopwords, cleaning, ...)
- Train of a Word2Vec model
- Build of the spark pipeline (Preprocessing, String To Index, ML, Index To String, ....)
- Check of the classification performances


# MIT License

Copyright (c) 2020 Mauro Pelucchi and Alessandro Vaccarino

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
