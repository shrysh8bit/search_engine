# search_engine
A basic search engine employing concepts of IR

Download the databse of articles from Wiki in txt files(not included due to large size), a 30MB archive contains appx 70k articles.

Extract the files and manually clean up files which aresimply refrences to the main article, this leaves us about 50k usable files.

Run the 4 ipynb files in order and prepare the inverted index. This step takes appx 24 hrs on an i5 processor.  

The queries are written in the queries.txt file and the 4_main.ipynb reads that file and returns the corresponding articles. It takes appx 3-5s for the query to return a result. 
