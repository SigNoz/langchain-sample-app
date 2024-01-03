# ChatPDF App

This is a sample ChatPDF app built using Langchain.

## Installation

1. Clone the repository:

    ```shell
    git clone https://github.com/SigNoz/langchain-sample-app.git
    ```

2. Navigate to the project directory:

    ```shell
    cd ChatPDF
    ```

3. Create and activate a virtual environment:

    ```shell
    python3 -m venv venv
    . ./venv/bin/activate
    ```

4. Install the required dependencies:

    ```shell
    pip install -r requirements.txt
    ```



## Usage

### Sign up for SigNoz cloud and get your access token

You can sign up for SigNoz cloud [here](https://signoz.io/teams/). You can get your access token and data region under setting --> ingestion settings.

![ingestion-settings](https://github.com/SigNoz/langchain-sample-app/assets/83692067/1b221075-a765-461a-a1ce-68df24e0dee3)


### Replace book.pdf with your PDF
```
curl https://www.w3.org/WAI/ER/tests/xhtml/testfiles/resources/pdf/dummy.pdf -o book.pdf
```

### Replace environment variables based 

### Run queries on book.pdf

```
. ./venv/bin/activate 
python main.py
```


## License

This project is licensed under the [MIT License](./LICENSE).
