conda create -n rag-tutorial-v2 -c conda-forge python=3.13

pip install -r requirements2.txt --upgrade

python populate_database.py
python query_data.py "in monopoly, how much money is given initially to each player?"

