# NLP-course-HSE

My learning codes when I learned NLP course given by HSE on Coursera.

🌍 __URL__: [homepage](https://www.coursera.org/learn/language-processing/home/welcome). <br />
🌍 __Official Github repository__: [this link](https://github.com/hse-aml/natural-language-processing). <br />
🖊 __My notes__ (for this course): [notion](https://www.notion.so/dinhanhthi/NLP-by-HSE-20cec3e92201475eb4d48787954f3aa4). <br />
📙 __My notes__ (in general): <https://dinhanhthi.com>. <br />
🔥 __My Data Science learning path__: [github repo](https://github.com/dinhanhthi/data-science-learning/tree/master/codecademy-data-science).

For setting up docker locally,

``` bash

docker pull akashin/coursera-aml-nlp
docker run -it -p 8085:8080 --name coursera-aml-nlp -v $PWD:/root/coursera --gpus all akashin/coursera-aml-nlp

# inside container "coursera-aml-nlp", run the notebook
run_notebook
# then go: http://localhost:8085/tree/coursera

# stop container
docker stop coursera-aml-nlp

# start container
docker start -i coursera-aml-nlp
```