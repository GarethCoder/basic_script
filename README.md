## Bash Script Learning

#### basicscript.sh 

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

#### pwdScript.sh

1. `` touch `` file called `` pwdScript.sh ``

2. Open `` pwdScript.sh `` and add the following:

```
#!/bin/bash

# Output the current directory

echo "The current directory is $(pwd)"

3. Alternatively you can save the pwd env var in a variable for example:

```
cDir=$(pwd)

echo "The current directory is ${output}"

```

