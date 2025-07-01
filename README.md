# JPE Report Template 

## Required Tools to use Template

1. Install [Quarto](https://quarto.org/docs/get-started/) to compile the report. 
   1. Quarto works more like latex and less then Word: you need to include all inputs to the document (like pictures) if sharing with others, or those elements will not appear.
   2. Given that *sharing* here works via `git`, you will have to `commit` all the files I need to compile your report.
2. `git` 
3. `VScode`: you should install the [markdown paste](https://marketplace.visualstudio.com/items/?itemName=telesoho.vscode-markdown-paste-image) extension to easily paste screenshots into the `.qmd` file.

## Outline

* clone this repo to a findable location on your computer (maybe `~/JPE-replications`?). Click on the green button "Code"
* If so, you will have `~/JPE-replications/JPE-Authorname-12345678` on your machine. You will work inside this folder.
* The content of this repo right now is:

```
.
├── _quarto.yml
├── _variables.yml
├── generated
├── images
├── LICENSE
├── package-output-map.xlsx
├── README.md
└── TEMPLATE.qmd
```

Few remarks:

1. You will edit the file `TEMPLATE.qmd` in your text editor (VScode ideally). 
2. Your screenshots will be saved to `images/`. 
3. The files `_quarto.yml` and `_variables.yml` are generated inputs for the template, as is the content of the `generated/` folder.
4. the folder `paper-appendices` contains pdf versions of paper and appendices for you to compare to.

## Next Step

* In your assignment email, there was a link to a dropox folder. Download and unzip the replication package as `replication-package` **into this repository**. That is, your repo should look like this after you downloaded the package:

```
.
├── _quarto.yml
├── _variables.yml
├── generated
├── images
├── LICENSE
├── replication-package
├── package-output-map.xlsx
├── README.md
└── TEMPLATE.qmd
```

* Notice that `replication-package` is the unzipped version of the package.
* The same dropbox link also contains paper and appendices in the directory `paper-appendices`. You should download those as well.


## Recommended workflow

1. Get VScode
2. install [markdown paste](https://marketplace.visualstudio.com/items/?itemName=telesoho.vscode-markdown-paste-image) extension
3. Go to [https://jpe-reproducibility.github.io/jpereplicators/](https://jpe-reproducibility.github.io/jpereplicators/) for step by step guidance.


