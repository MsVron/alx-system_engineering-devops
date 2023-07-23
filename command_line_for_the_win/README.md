# cmd challenge

Step-by-step instructions on how to submit the project screenshots via SFTP and GitHub:

### Step 1: Capture Screenshots

Capture screenshots of the completed levels as specified in the general requirements.

### Step 2: Open Terminal

Open a Terminal or Command Prompt on your local machine.

### Step 3: Establish SFTP Connection

Use the SFTP command-line tool to establish a connection with the sandbox environment. Replace `your_username`, `your_password`, and `hostname` with your actual credentials.
```
sftp your_username@hostname
```
When prompted, enter your password.

### Step 4: Navigate to Target Directory
Once you're connected, navigate to the directory on the sandbox environment where you intend to upload the screenshots.
```
cd target_directory
```

### Step 5: Upload Screenshots
Use the put command of the SFTP to upload the screenshots from your local machine to the sandbox environment. Replace local_filepath with the path to your screenshots on your local machine.
```
put local_filepath
```

### Step 6: Confirm Transfer
Confirm that the screenshots have been successfully transferred by checking the content of the sandbox directory.

```
ls
```

### Step 7: Push Screenshots to GitHub
After the successful transfer of the screenshots to the sandbox environment, proceed to push the screenshots to your GitHub repository as mentioned in the initial requirements.
