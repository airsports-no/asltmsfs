```
cd MSFS2020_client
python -m build
cd ..
pyoxidizer run
```
```
pyinstaller -F --onefile --add-data "client/airsports.png;." --add-data "client/SimConnectCust;client/SimConnectCust" --noconsole client/airsports_client.py
```
