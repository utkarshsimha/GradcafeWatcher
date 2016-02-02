Install dependencies using pip :

pip install -r requirements.txt

If you are using Mac OSX, please comment out "notify2" package and uncomment "pync" package in requirements.txt
If you are using Linux, please comment out "pync" package and uncomment "notify2" package in requirements.txt

Open the python script and update your STREAM, UNIVERSITY LIST and REFRESH INTERVAL

ALL UPDATES ARE WRITTEN ONTO A FILE - update.txt

Run the python script, in background and not associated with the terminal as :

nohup python gradcafe_notifier.py &
