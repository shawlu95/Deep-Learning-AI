### Download Jupyter Workspace files

If you’ve completed Jupyter notebook assignments in a Coursera course, you can download your files so you can run them locally once the course ends. Your files will not stay on Coursera indefinitely, so you'll need to download them if you want to keep them.

#### Download a single notebook

To download a single notebook:

Open the notebook you want to download
Click File
Click Download As
Choose a file format, then download your notebook.

#### Download all of your notebooks at the same time

To download all of your Jupyter Workspace files at the same time:

Launch one of your notebooks from coursera.org
In the upper right, click the Coursera logo
You'll see a file view page that lists all Jupyter resources in your current course. Click the New, then select Terminal to open the system command line.
You'll see a shell prompt open. In the shell prompt, type or paste the following statements:

Remove the previous archive, if it exists: 
```bash
rm -f ~/workspace.tar.gz && rm  -f ~/work/workspace.tar.gz
```

Create a zipped archive of your workspace directory: 
```bash
tar -czf workspace.tar.gz ~/work
```

Move the archive into the workspace directory so you can see it: 
```bash
mv ~/workspace.tar.gz ~/work/workspace.tar.gz
```

Once the commands run successfully, click on the ‘Coursera’ logo again to return to the file view.
In the file view, select workspace.tar.gz, then click Download. Your browser will download the workspace archive, which is yours to keep.

[More](https://coolestguidesontheplanet.com/how-to-compress-and-uncompress-files-and-folders-in-os-x-lion-10-7-using-terminal/)