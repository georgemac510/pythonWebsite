<h1>Welcome to the McKurz Capital financial charts app</h1>

<h3>Prerequisites are installation of python and pip. These directions were used on an Ubuntu 18.04 installation</h3>

<h2>Steps to clone our repo and start the app</h2>

<h2>Step 1: Make directory and cd into it</h2>

      mkdir finpython
      cd finpython

<h2>Step 2: Create git repository and clone repository

      git init
      git clone https://github.com/georgemac510/python1website.git
      cd python1website

<h2>Step 3: Creating python virtual machine instance using virtualenv</h2>

      pip install virtualenv
      python -m virtualenv virtual
      cd virtual

<h2>Step 4: Install dependencies using pip</h2>

      pip install flask
      pip install bokeh
      pip install pandas
      pip install pandas_datareader

If errors,

      python -m pip install --upgrade pip

then try to install the "error" dependency again.

<h2>Step 5: Start app and explore</h2>

      cd ..
      python script1.py

This will start your virtual instance. Navigate to http://127.0.0.1:5000/ and the app
will open in your browser. On the top right on the navigation bar click on Plot. If all is well,
you should see a stock chart of the company Rio Tinto during the first half of 2020.

More improvements to come. Stay tuned!

Visit us at https://mckurzcapital.com to see our other projects
