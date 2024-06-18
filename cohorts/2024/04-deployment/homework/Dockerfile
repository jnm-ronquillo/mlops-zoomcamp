FROM agrigorev/zoomcamp-model:mlops-2024-3.10.13-slim

RUN pip install scikit-learn==1.5.0 pandas pyarrow

COPY my_solution.py .

ENTRYPOINT [ "python", "my_solution.py" ]