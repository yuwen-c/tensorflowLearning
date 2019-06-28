# 1. download data:
Resources for this lecture
FULL_TENSORFLOW_NOTES__AND_DATA.zip

# 2. for macOS and Linux user: download the alternative .yml files,
otherwise there will be a error message.

# 3. download from: anaconda.com/download
choose Windows, macOs, or Linux system
*I choose macOs, python 3.7, graphical installation
for Windows user, mark "add ANACONDA to my path environment variable"

# 4. create environment file and activate it:
then use cmd/ terminal to restore the environment files
make sure you have alredy unzipped the tensorflow-bootcamp
*in mac is tensorflow-bootcamp master
enter it and there is .yml file and some files like this: 00, 01...
go to that directory and run this command:
$ conda env create -f mac_tfdl_env.yml 
*for mac

# 5. activate it: (go to a virtual environment)
* for mac
To activate this environment, use
    $ conda activate tfdeeplearning
To deactivate an active environment, use
    $ conda deactivate

# 6. jupyter notebook
run this line:$ jupyter notebook
pop over to a browser: jupyter
if not: copy paste the url and token to the browser.

open a new file (choose python3)
enter this code to see if it runs well:
 import tensorflow as tf
 hello= tf.constant("hello world")
 sess=tf.Session()
 print(sess.run(hello))
=>b'hello world'

# 7. something about jupyter notebook
1. view > toggle header, toggle toolbar
2. rename the title
3. select code or markdown
4. define s='string', then type s+.+tab, then it will give you all the method
5. s.capitalize + tab, it will show the document
6. insert cell above or below

