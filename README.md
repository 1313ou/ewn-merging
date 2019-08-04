# ewn-merginf
XML merging of English Wordnet lexical files

A XSL are provided to do the merging with a Saxon parser supporting XSLT 3.0

*Needed:*

* java runtime >= 8

* run.sh

* Saxon-HE-9.9.1-4.jar

* merge-lexfiles.xsl


*How to run:*

```
./run.sh dir (merged_file) 
```

dir is where the lex files are
merged_file is where the result is saved (if absent, the result is sent to stdout)