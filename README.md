How to save this project to Linux:

1- git clone https://github.com/muhammadkmal27/Project-XSS-Linux.git

2- cd Project-XSS-Linux/

Here is the method to install the required requirements:

1- Download Chrome from the official website: https://www.google.com/chrome/

2- Here is the Linux command after download:

   cd ~/Downloads
   
   sudo dpkg -i google-chrome-stable_current_amd64.deb
   
   google-chrome --version
   
3- Create a virtual environment:

   Example:
   
   python3 -m venv akmal
   
   source /home/kali/akmal/bin/activate
   
3- Install requirements:

   pip install -r requirements.txt
   
4- To Run c_breakers:

   python c_breakers.py

How to use after installing all the requirements:

1- source /home/kali/akmal/bin/activate

2- python c_breakers.py


Note:

Our tool uses "URL PARAMETERS," not regular URLs. If you don’t know what URL parameters are, you can search on Google to learn more.

Make sure you use the three tools I have listed to obtain URL parameters before using our tool:

1- subfinder
   
How to download: sudo apt install subfinder

How to use: subfinder -d example.com

Save subdomains: nano sub.txt (press Ctrl + O to save)

2- httpx-toolkit

How to download: sudo apt install httpx-toolkit

How to use: httpx-toolkit -l sub.txt

3- paramspider

How to download: sudo apt install paramspider

How to use: paramspider -d https://www.example.com/page?key1=value1&key2=value2 (choose one of the URL parameters)
