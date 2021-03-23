<div>
  
</div>


# Gretl-logit-test

Script for the Data Science A-Z by SuperDataScience course. Allows for very simple model testing without the limitations of the point & click interface of Gretl.

Keep in mind that it has a questionable quality, but it does the job.

Thanks to the Gretl user list guys for helping me too :)

## How-to

The script is pretty much self explanatory. Download the .INP files (csvs should already be provided, but the ones in the repo are valid too), double click ``applying-model-to-test-data.inp``, and follow the instructions contained in the comments.

It has been tested in Windows and Linux, with Gretl 2019a

## Output

The script saves two files.

- training-output.csv -> Contains RowNumber, Exited and the model probability scores
- forecast-output.csv -> Contains RowNumber and the testing probability scores


## References for learning about Gretl scripting

Gretl has not been subject to much attention outside academia, I guess because the documentation is a bit lacking, with mostly PDFs in the wild. It is a nice little self-contained tool though.

If you're looking for documentation:

- For the total beginner: [The Gretl guide](http://gretl.sourceforge.net/gretl-help/gretl-guide.pdf) (PDF)
- Assuming you know a bit of programming already: [Hansl Primer](http://ricardo.ecn.wfu.edu/pub/gretl/manual/PDF/hansl-primer-a4.pdf) (PDF)

- HTML references: [Command Reference](http://gretl.sourceforge.net/gretl-help/cmdref.html) & [Function Reference](http://gretl.sourceforge.net/gretl-help/funcref.html)

