# InformationRetrieval

An information retrieval system for Italians schools has been developed using **Solr** platform.

The Italian schools dataset released by *MIUR* (Ministry of Education, Universities and Research) was downloaded in CSV format and processed with ETL tools. Data have been cleaned by using **Kettle**, performing operations such as URLs correction, whitespace removal and other syntactical corrections.
Then the dataset has been loaded on **Solr**, an open source search platform, written in Java, from the Apache Lucene project. Configuration parameters have been set and fields for querying and faceting have been created. Functions as synonyms recognition and spellcheck for *autocomplete* and *did you mean?* features have been added too. 
Finally a catchy graphical user interface (with map function and others) has been created by using *Velocity*.

Please see *Information Retrieval System.pdf* for implementation details and *demo.mp4* for a practical usage demonstration.
