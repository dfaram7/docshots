# docshots
Finding sensitive information in the trimmed parts of cropped images 


Cropping pictures inserted in a microsoft word document enables users to hide parts of a picture that they do not want to display. The problem is that Office’s cropping tool only modifies how the cropped image is displayed in the body of the document. The original picture remains intact. Cropped portions of the image are not completely removed from the document and can be seen by others if the file is uploaded to the internet. Data leakage can occur if there is sensitive data in the trimmed areas.

Docshots searches google for documents (docx) by query, downloads them and checks for images where cropping has occured.

This solution uses goog.io, They have free and commercial packages available.

It is advised that you run the notebook in a sandbox or vm as it does involve downloading untrusted documents from the internet.


Clone the repository

`git clone https://github.com/dfaram7/docshots.git`


Install the requirements

`pip install -r requirements.txt`

Run the notebook!

`jupyter notebook`

