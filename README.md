# genaimongodb
gen ai access mongodb vector search, runs on rancher desktop

python: Python 3.11.6

## init ollama by helm chart or by ollama install tools
helm install ollama ollama-helm/ollama --namespace ollama --values values.yaml

## install environment
pip3 install -r requirements.txt

## run your application
streamlit run main.py


## test query string
show me movies about looney tunes and outer spaces

## docker build
