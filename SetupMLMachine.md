
# Set up Jupyter Notebook server
* NoIP
  * Set ip to be toondesktop.ddns.net
  * Set up port forwording on my TP-link to my desktop computer

--
* Window Setup
  * Based on this https://medium.com/@joelclay/access-your-jupyter-notebook-running-on-windows-10-from-any-computer-427bb06309ce
  * To Start
    * Run terminal from conda root environment to get activated environment
    * `C:\Users\Toon\Anaconda3\python.exe C:\Users\Toon\Anaconda3\cwp.py C:\Users\Toon\Anaconda3 C:\Users\Toon\Anaconda3\python.exe C:\Users\Toon\Anaconda3\Scripts\jupyter-notebook-script.py`
  * Current Configration looks like this
    ``` {
     "NotebookApp": {
      "password": "sha1:...",
	"open_browser": false,
        "port": 8000,
         "ip": "*",
         "notebook_dir": "E:\\HumanAtlas",
	 "SSL..."
         }
     }
    ```
--
* Linux
  * I had problem with nvidia docker.
    * Solve by https://github.com/nvidia/nvidia-container-runtime#docker-engine-setup
      * restart `service start/stop docker`
  * Another problem when running jupyer notebook
    * Need to regenerate config
    * Then specify `127.0.0.1` address. `jupyter notebook --ip 127.0.0.1`
  * Use option that I build Docker File locally.
    * Dockerfile is at https://github.com/tsripata/toon_ml_machine
    * Instruction to run is in the Github

--
