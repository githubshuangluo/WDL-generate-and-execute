# WDL-generate-and-execute
Writing a WDL
First, we'll introduce the building blocks of WDL and how they fit together to form the base structure of a WDL script. Then we'll show how to add variables so that input files and parameters can be specified outside of the script itself, which will allow you to use the same script for different runs without modification. Next, we'll cover how to add plumbing, i.e. how you can chain together the components that perform units of work in different ways to form sophisticated pipelines. Finally we'll look at how to validate syntax, which sounds boring but is really helpful since it will tell you quickly whether your WDL script is runnable or not. Because nobody likes starting a run only to see it fail because it's missing a semi-colon somewhere.

Do as follows:    
[Base structure](https://software.broadinstitute.org/wdl/documentation/structure.php).       
[Add variables](https://software.broadinstitute.org/wdl/documentation/variables.php).   
[Add Plumbing](https://software.broadinstitute.org/wdl/documentation/plumbing.php).   
[Validate Syntax](https://software.broadinstitute.org/wdl/documentation/validation.php).   

Running a WDL
This is going to be short and sweet. We'll show you how to generate a JSON template for specifying inputs (spoiler: it's super easy) and fill it out. Then we'll present the main options for executing your WDL script, focusing on the execution engine we use in our own work, which is called Cromwell. If you had asked us two years ago if we'd ever have an execution engine that we could use both in development and in production, locally and on the cloud, we would have said when pigs fly...
    
[Specify Inputs](https://software.broadinstitute.org/wdl/documentation/inputs.php).   
[Execute!](https://software.broadinstitute.org/wdl/documentation/execution.php).   

When you're ready.   

Once you have grokked the core concepts involved in writing and running WDL workflows, the next step will be to actually do it yourself! In the [Tutorials](https://software.broadinstitute.org/wdl/documentation/topic?name=wdl-tutorials) section, we provide a series of fully worked-out "build-a-WDL" examples in which we walk you through each step of composing workflows that demo all the key features of WDL. For best effects, work your way through the tutorials in the order suggested on the Tutorials page.    

For a wider variety of use cases, you can also browse the [Real Workflows](https://software.broadinstitute.org/wdl/documentation/topic?name=wdl-scripts) which are scripts that address real analysis problems and that we in our own work. This includes the Broad Genomics production pipelines for variant discovery in exomes and whole genomes.    

What you'll need.   
Below is a list of the basic requirements / things you need to get in order to run workflows written in WDL (using the Cromwell execution engine, because that's what we use), with installation instructions where necessary. Because we use GATK in most of the tutorials and example WDL scripts on this website, we include a link to GATK installation instructions as well, but this is optional if you don’t plan to run the GATK WDLs.    

There are additional resources that may help you work with WDL; see the [Toolkit](https://software.broadinstitute.org/wdl/toolkit) page for a full list.    

[What to get and how to install it](https://software.broadinstitute.org/wdl/documentation/quickstart).   
