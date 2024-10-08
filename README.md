##FTP instructions (https://submit.ncbi.nlm.nih.gov/subs/sra/#files_upload_ftp)

    Navigate to the source folder where the files for submission are.
    Establish an FTP connection using the credentials below:
    Address: ftp-private.ncbi.nlm.nih.gov
    Username: subftp
    Password: XXXX
    Please do not share these log-in credentials. Do not include these log-in credentials on a public page. These credentials are changed regularly, as per our security policies.
    Navigate to your account folder:

    From the command line use the 'cd' command:
    cd uploads/inneke_usp.br_97KJCQI2

    When using a GUI FTP client (eg: Filezilla, NcFTP, Cyberduck, etc.), after you’ve connected to the FTP server, paste your account folder (uploads/inneke_usp.br_97KJCQI2) into the “Remote Site” or “Remote Directory” box on the interface and press “Enter”.

    Then you will be able to create the data sub-directory for your submission. Until you do this, you will see a message stating "550 /: Permission denied" or "Failed to read the directory listing". We prevent directory listing in the default sign in folder for security reasons.
    Create a subfolder (required!) with a meaningful name:
    mkdir new_folder

    Note: Use ASCII text only for folder and file names.
    Navigate to the target folder you just created:
    cd new_folder
    Copy your files into the target folder:
    put file_name
    To copy all files
    mput * 

    Note: If you upload your files to your account-level directory, you will not be able to use them in your submission. Files uploaded to the account level will be moved to a directory named moved_by_ncbi and subject to deletion after 30 days of inactivity. Therefore please transfer files to a directory inside your account-level directory.

Last, return back to this page to submit.
