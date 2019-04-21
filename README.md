

Download http://archive.apache.org/dist/lucene/solr/7.5.0/solr-7.5.0.zip

unzip the file

once unzipped go to the directory 
execute 

bin/solr start

once completed , go to the browser - localhost:8983 , 

you should be able to see solr up and running

then 

from command line execute - bin/solr create_core -c  words


Once done to the browser localhost:8983/

on the left hand side, there is a core_selector. From the dropdown box, select "words"

From there click on "Documents"

On the tight hand side, in the text box, cut and paste the contents from the attached file and click on the submit button.

Once done, click on the query button on left side .

Then click on the execute Query button.If the results are displayed on right hand side, then we are ready to test the application