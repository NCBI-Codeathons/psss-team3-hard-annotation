# Mock Search

This directory represents what a consumer would need to provide in order to run
the benchmark against "the_count". Compared to mock-search, it's a more realistic 
example that uses an existing docker image to run the script wrapping the tool.

```
docker build -t psss-harness .
```

This should be the only command you need to run to continue benchmarking the software. 
Next, cd ../ and run the nextflow commands using the psss-harness docker image.