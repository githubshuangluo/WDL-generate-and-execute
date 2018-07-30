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
