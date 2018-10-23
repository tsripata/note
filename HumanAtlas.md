# Set up Jupyter Notebook
* NoIP
  * Set ip to be toondesktop.ddns.net
  * Set up port forwording on my TP-link to my desktop computer
* Did not setup the cert yet
* https://medium.com/@joelclay/access-your-jupyter-notebook-running-on-windows-10-from-any-computer-427bb06309ce
* To Start
  * `C:\Users\Toon\Anaconda3\python.exe C:\Users\Toon\Anaconda3\cwp.py C:\Users\Toon\Anaconda3 C:\Users\Toon\Anaconda3\python.exe C:\Users\Toon\Anaconda3\Scripts\jupyter-notebook-script.py`
  * Configration looks like this
    ```
    {

  "NotebookApp": {

    "password": "sha1:...",

	"open_browser": false,

    "port": 8000,

    "ip": "*",

    "notebook_dir": "E:\\HumanAtlas"

  }

   }
    ```
