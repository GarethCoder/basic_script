#### Bash Script Learning

- Basic bash scipts to create a file.

1. Use ``touch`` cmd to create a file called `` basicscript.sh ``.

2. Open `` basicscript.sh `` in editor or in terminal using pref terminal editor ie. `` vim ``, `` nano ``.

3. Add the following to the file: 

```
#!/bin/bash

touch tempfile.txt
chmod 777 tempfile.txt

```

4. Save and Exit. Run the file as follows `` bash basicscript.sh ``

5. Alternatively you can make the file an executable run `` chmod 775 basicscript.sh ``
   then the file can be executed with `` ./basicscript.sh ``.