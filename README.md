w## Run it

```
pip install -r requirements.txt
python app.py
```
```
docker build -t app-remove-bg-python .
```
```
docker run -p 5111:5100 app-remove-bg-python
```