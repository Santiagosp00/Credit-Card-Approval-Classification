<h1 align="center">
        <samp>Credit Card Approval Classification Project   </a></b>
        </samp>
</h1>

<p align="center"> 
  <samp>
    [ Welcome to the project that makes classification of credit card applications to be accepted or not,
    <br>
     depending on historic clients behaviour and similar applications information.]
    <br>
  </samp>
</p>

<div align="center">
    <img src="https://www.shutterstock.com/image-vector/payment-approved-outline-icon-credit-600nw-2237221801.jpg" alt="credit_card_image" />

</div>


- [Summary](#summary)
- [Demo](#demo)
- [Project structure](#project-structure)
- [Working with the repo](#working-with-the-repo)


## Summary

In the Financial industry, different risk control methods emerges when different products are offered. One case is the Credit score cards for Credit Card applications. It is used personal information and submitted data from applicants to predict probabilities of defaults or borrowings. With this outcome, the bank is able to decide whether to issue a credit card to the applicant. Even though there are many options, in this case I consider credit scores to be the main procedure to quantify risk. 

Taking that as a context, the general proccess is bases on historical data, and is largely dependant of economic fluctuations. It is common and is necessary to update continuously the models to keep the predicitive power. My objective for this project is to deliver a more powerful model, since Logistic models are the base option. The task is to improve and to have a ceratinty of transparency of the decision that is good enough for customers and regulators when they are rejected or accepted.

## Demo

The project includes an interactive web app. It allows to make the application and have the decision right away. It is just a matter of filling the information. The app is built in Python using the Streamlit package. 

## Project structure

The project is simple and has the following structure:
- `data/`: `.csv` files containing the datasets needed for the project
- `notebook/`: `.ipynb` Colab-friendly notebook with the EDA, data featuring and model training.

## Working with the repo

### Environment

To work with the repo, I recommend creating a virtual Conda environment from the `project_environment.yml` file:

```
conda env create --name read --file project_environment.yml
conda activate read
```

The file `requirements.txt` provides the list of dependencies for the web app.

### Reproducing Solution

The solution can be reproduced by running the notebook. Even though, the outputs of the cells are visible in case you only want to inspect the project. 


More details are provided in the documentation within the notebook.