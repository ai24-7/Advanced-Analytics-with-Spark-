Advanced Analytics with Spark Source Code
=========================================
### Running the Examples
- Install [Apache Spark](https://spark.apache.org) for your platform, following the instructions for the [latest release](https://spark.apache.org/docs/latest/).
- Build the projects according the instructions above.
- Launch the driver program using `spark-submit`
```bash
# working directory should be your Apache Spark installation root
bin/spark-submit /path/to/code/aas/$CHAPTER/target/$CHAPTER-jar-with-dependencies-$VERSION.jar
```
- Some examples might require that URI paths to the data be updated to your own HDFS or local filesystem locations.

### Data Sets

- Chapter 2: https://archive.ics.uci.edu/ml/machine-learning-databases/00210/
- Chapter 3: https://storage.googleapis.com/aas-data-sets/profiledata_06-May-2005.tar.gz
- Chapter 4: https://archive.ics.uci.edu/ml/machine-learning-databases/covtype/
- Chapter 5: https://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html (do _not_ use http://www.sigkdd.org/kdd-cup-1999-computer-network-intrusion-detection as the copy has a corrupted line)
- Chapter 6: https://dumps.wikimedia.org/enwiki/latest/enwiki-latest-pages-articles-multistream.xml.bz2
- Chapter 7: ftp://ftp.nlm.nih.gov/nlmdata/sample/medline/ (`*.gz`)
- Chapter 8: https://storage.googleapis.com/aas-data-sets/trip_data_1.csv.zip (from http://www.andresmh.com/nyctaxitrips/)
- Chapter 9: See https://github.com/sryza/aas/tree/master/ch09-risk/data ; included download scripts no longer work
- Chapter 10: ftp://ftp.ncbi.nih.gov/1000genomes/ftp/phase3/data/HG00103/alignment/HG00103.mapped.ILLUMINA.bwa.GBR.low_coverage.20120522.bam
- Chapter 11: https://github.com/thunder-project/thunder/tree/v0.4.1/python/thunder/utils/data/fish/tif-stack

[![Build Status](https://travis-ci.org/sryza/aas.png?branch=master)](https://travis-ci.org/sryza/aas)
