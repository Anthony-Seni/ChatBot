# Chatbot
This chatbot is built as an open domain question and answering using Facebook QA system. You can access the web app [HERE](https://askurimmendpoint.ml)


# Installing
DrQA Web UI requires Linux/OSX and Python 3.5 or higher. 

1. Install DrQA [Link](https://github.com/facebookresearch/DrQA)
2. Install dependencies (`pip install -r requirements`)
3. Set `drqa_data_directory` in `services\__init__.py` to data directory of DrQA
4. Run (`gunicorn --timeout 300 index:app`)

# License
MIT