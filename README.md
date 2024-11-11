# pororo

PORORO (Platform Of neuRal mOdels for natuRal language prOcessing) has been archived by the owner as of May 27, 2022.
Due to this, it’s no longer possible to address errors that may occur during the installation of the library. Therefore,
I have modified some parts of the code. If you plan to use the PORORO library, you may need to update certain parts of
the repository code as well.


### Installation Guide for PORORO   
The original PORORO repository can be found [here](https://github.com/kakaobrain/pororo). Since it has been archived and may not work with recent Python or pip versions, please follow these steps to use the library with some necessary code modifications.

0. Clone the Repository
    ```angular2html
    !git clone https://github.com/kakaobrain/pororo
    ```
1. Modify the Code You need to update two files from the repository. Use the modified versions from my repository:
   * setup.py
   * pororo/tasks/utils/tokenizer.py


2. Set Pip Version Make sure to downgrade your pip version to avoid compatibility issues:
    ```angular2html
    !pip install "pip<24.1"
    ```
3. Install PORORO
    ```
   cd pororo
   pip install .
   ```