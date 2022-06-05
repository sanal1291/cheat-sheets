<!-- venv -->
pip install virtualenv
<!-- create env -->
python -m venv <env name>
<!-- acitvate -->
.\env\scripts\activate
<linux> source .\env\scripts\activate
<!-- install modules -->
pip install <package name>
<!-- end -->

<!-- fastapi -->
pip install fastapi
pip install "uvicorn[standard]"

<!-- start server -->
uvicorn main:app --reload