# Compile this TeX article

## What this 'project' is about

This project helps you calculate the GDP of your island in the game _Animal Crossing_.

## How to generate the PDF file by compilation

This project uses LaTeX.
The `main.tex` file contains what's written in the article, along with typesetting information.
A LaTeX _compiler_ takes content and typesetting information into account to visualize the layout and put the pieces together to create a final PDF document.
This process is automatic and part of the LaTeX system.
There are many options for setting up a LaTeX system.

You can install a LaTeX package on your computer and run the compilation yourself.
On Ubuntu, you can install the `texlive-full` package, which (at the time of writing) will cost about 6 gigabytes of hard disk storage after installation.
Then, you call `mklatex`.
MacOS and Windows also have established and popular TeX distributions.
On MacOS, MacTeX seems to be very popular.
On Windows, MikTeX is the established brand.

You can also use an online service that takes care of the operations.
A good example is [Overleaf](https://www.overleaf.com), which used to fly under the label Sharelatex.
To use Overleaf, you must be logged into the service.
Create an account or use your registered account.
Next, you must import this project.
You can download and ZIP-compress the repository, and upload the ZIP file.
Or, you can fork this repository into GitHub, with which they have integrated, and set up sync.
After your project is loaded, just click the _Compile_ or _PDF_ button.
You can download the PDF file by going to _Menu_ and clicking on the _PDF_ button.

There are costs and benefits to each approach.

The local installation path takes some amount of initial investment.
A typical installation can take 3-15 minutes depending on the environment.
It will also cost some amount to download the data from the internet.
It takes gigabytes on your storage.
Each computer requires a different installation.
Lastly, a bad LaTeX installation can make your computer vulnerable to intrusions, since LaTeX comes not only with just data but also executable binaries and scripts.

On the other hand, you do not need to pay anyone anything for using LaTeX on your own computer.
All online subscriptions come at a price, but a local service will be free.

An online service like Overleaf can be expensive.
It may not contain all the packages you need, or all versions of TeX.
However, all the commonly used packages are managed by them, and competitive ones are managed well.
Also, Overleaf, in particular, has fantastic LaTeX documentation that is freely accessible to everyone.
