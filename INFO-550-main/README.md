# INFO 550
## My project

For my project, I will analyze  `ProjectA` data. 

This project used linear regression to test the relationship between CPC counts and obsetity. 

## Set up

To analyze the data, you will need to have R installed and synchronize your package library.

After download the repository, navigate to the project directory on your computer. 

Open an R session in your terminal. Synchronize your package library using the following command:  

```{r}

renv::restore()

```
Quit R using the command `q()`.

## Run the analysis 

To run the analysis and generate the results report, run the following command in your terminal from the INFO550-project directory: 

```{r}

make report.html

```

This will create a file called `INFO-555-HW2-YajieLiu.html`. You can open the html file in your browser to view results. 

## Trouble shooting
If you have problem when synchronize the package library, please try the comman line below to install the gcc:

```{r}
brew install gcc
```
