# idea-formatter

Format your code using Intellij IDEA Community Edition

# Usage

`docker run --volume $PWD:/srv --env "MASK=*.kt" artemyarulin/idea-formatter`

- `$PWD` The path to a file or directory to be processed
- `MASK` A comma-separated list of file masks which defines the files to be processed. Wildcards * (any string) and ? (any single character) are supported
