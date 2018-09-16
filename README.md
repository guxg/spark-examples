
# Maven

Use Maven to build the examples.

## Dependency

http://repo.maven.apache.org/maven2/org/apache/spark/

> netlib-java

https://spark.apache.org/docs/latest/ml-guide.html#dependencies

https://github.com/fommil/netlib-java

```
Failed to load implementation from: com.github.fommil.netlib.NativeSystemBLAS
Failed to load implementation from: com.github.fommil.netlib.NativeRefBLAS
```

# Running

## bin/run-examples

https://spark.apache.org/docs/latest/#running-the-examples-and-shell


## IDE

### VM options

-Dspark.master=local -Dspark.sql.warehouse.dir=out

### Program arguments

> ml.LinearRegressionExample

--regParam 0.15 --elasticNetParam 1.0 /usr/local/spark-2.3.1-bin-hadoop2.7/data/mllib/sample_linear_regression_data.txt


> SparkLR

