## Instructions on running the program

Please note that the staging and production databases are hosted on an Azure server, on my personal account. So in order to connect please update the credentials lines in line 16-31 of the notebook. The credentials file is sent in an email. This is dummy data so we should be fine using this approach.

The two '.numbers' extension files were first converted to csv and then placed in an Azure Storage blob, and the credentials to which are in the code. However, since the data is fake, and the account is my private Azure account, it should not be an issue for this test case. This kind of approach is otherwise highly unadvisable in a company setting.

Please note, that the test cases can be found in the second cell of the jupyter notebook attached. (There are two files one in HTML and the other in .ipynb extension, but they are the same program)

### To test the program:

1. Update the credentials in line 16-31, from the file supplied in email.
2. Just run the program in a spark-enabled environment.
3. I have opened all incoming connections to my postgresql databases for this demonstration.
4. The program should display some logs and would store the final refined data in 'unique_providers' and 'unique_clinicians' tables.
5. For verifying, you can also check the other staging and production environment tables.

Note: I have made some other assumptions that can be found in the notebook.
