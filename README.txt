 Create a README file that includes notes describing where in the code to find the changes you made for each
 of parts C to J. Each note should include the prompt, file name, line number, and change.

 C.
    Line 14: Added link to a CSS style sheet                        (mainscreen.html)
    Line 15: Changed Title to "Computer Shop"                       (mainscreen.html)
    Line 16: Added link to a favicon                                (mainscreen.html)
    Line 23: Changed header to "Computer Shop"                      (mainscreen.html)

    Line 1-13 Changed webpage styling                               (styles.css)

    Added directory "images" and icon                               (src/main/resources/static/images/computer.ico)

 D.
    Line 25-30: Added nav elements as a list of links               (mainscreen.html)

    Line 14+ Styled nav elements and About page                     (styles.css)

    Created AboutController Class                                   (AboutController.java)

    Created about.html and wrote an about section                   (about.html)

 E.
    Line 44-101:                                                    (BootStrapData.java)
    Wrote an if statement to check if any parts or products were in
    the repository. If there were none, created 6 parts and five
    products to populate the repositories as examples.

 F.
    Line 96-97:
    Added a button to buy product, passes along product id          (mainscreen.html)

    Created a controller class for "/purchaseproduct" which         (PurchaseController)
    decreases product inventory by 1 if it is in stock
    and shows a confirmation page, else it shows an error
    page

    Created a view which shows a confirmation of purchase           (confirmationpurchaseproduct.html)

    Created a view which shows a failed purchase                    (failedpurchaseproduct)

 G.
    Line 32-35: Added min and max values                            (Part.java)
    Line 106: Added validInv() function to check that inventory     (Part.java)
    is between max and min.

    Line 23: Added error message when inventory is not between      (InhousePartForm.html)
    maximum and minimum

    Line 42: Added condition to check validInv() and wait for       (AddInhousePartController.java)
    correction if it returns false

    Line 24: Added error message when inventory is not between      (OutSourcePartForm.html)
        maximum and minimum

    Line 43: Added condition to check validInv() and wait for       (AddOutsourcePartController.java)
    correction if it returns false

    Lin 51~97: Added min and max values to example parts            (BootStrapData.java)

 H.
    Line 23-24: Created two statements, one checks if               (InhousePartForm.html)
    inventory is below the minimum and the other if it
    is above the maximum.

    Line 24-25: Created two statements, one checks if               (OutSourcePartForm.html)
    inventory is below the minimum and the other if it
    is above the maximum.

    Line 36: Added condition to check if inventory will go below    (EnufPartsValidator.java)
    minimum upon creating part

 I.
    Line 104-138: Created tests for getMin(), setMin(),             (PartTest.java)
    getMax(), and setMax().

 J.
    Deleted "DeletePartValidator" which had no implementations      (DeletePartValidator.java)
    Deleted all unused imports and functions, cleaned up all code.