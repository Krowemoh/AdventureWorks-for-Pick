# AdventureWorks for Pick

This is the sample AdventureWorks database for Pick. The CSVs are imported through a Pick program that will create the following files:

```
CUSTOMER-FILE
INVENTORY-FILE
ORDER-FILE

CATEGORY-TABLE
MODEL-TABLE
PRODUCT-DESCRIPTION-TABLE
```

To set everything up, create a DEMO account and run the IMPORT.PRODUCTS program.

```
RUN BP IMPORT.PRODUCTS
```

You will need to update the PATH variable in the program to point to the source directory of the csv files.
