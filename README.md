# Spatter Patterns

This repository contains memory access patterns used as input to the [Spatter](https://github.com/hpcgarage/spatter) benchmark.

To use these inputs, first build the benchmark, then run it as follows:

```
./spatter -pFILE=/path/to/pattern-file.json
```

## Contributing

To submit your patterns, please submit a PR with the following structure:

```
OrganizationName/
|- README.md
|- pattern1.json
|- pattern2.json
...
```

The README should include author names and information about the included patterns.
If you have recommendations for Spatter settings to use with your patterns,
or recommendations for machine parameters, please include those as well.
You are free to structure your patterns into subdirectories as you see fit.
