# Challenge 1 - Training from a Notebook

## Summary

You are working for a credit card company and are one of the few people who work on fraud detection models in this company.
You suddenly get an email from your boss saying that one of the models is experiencing some extreme model drift and needs to be replaced. They have already tried to retrain it themselves, but something didn't work and your colleague who is in charge of this model is up in the mountains today, so it's up to you to go and try to fix it.
You reach out to your colleague and through a weak signal get to hear that the model training script is saved in a GitHub repo (this one).
They also mention that they unfortunately are unable to share their Data Science Project and that you need to create one from scratch. They can't remember what image they used to train the model, but they do recall that a **small** container size is enough, and no GPU is required.
Finally, they recommend to just Google the RHODS documentation to get a general understand of how to navigate it and how Data Science Projects work.

## Todo

You make a list of what you need to do and get to work:

- Create a new Data Science project to get access to a Notebook and name it **RHODS-Train-01-<your_RH_username>**.
- Create a new Workbench inside the DS Project
- Clone this git repository ([https://github.com/rh-aiservices-bu/rhods-training/](https://github.com/rh-aiservices-bu/rhods-training/)) inside the project.
- Run the model training notebook (train_model.ipynb).
- Run an inference by using the model testing notebook (test_model.py).
- First, execute it to review whether Sally's transaction was deemed fraudulent or not.
- Then, add another cell to make a prediction for Jon's transaction. Here are the details for Jon
  - distance_from_last_transaction: 99999.9
  - ratio_to_median_price: 17
  - used_chip: 1.0
  - used_pin_number: 0.0
  - online_order: 1.0
- Make a good note of the result for Jon, as it will be a question in the last quiz

## Important

(But by all means, ignore the section called **IMPORTANT**)

Once you have completed these steps, you have to:
- Stop your running workbench
- Delete your Data Science Project (**RHODS-Train-01-<your_RH_username>**)

We will periodically check the environment to make sure you did not forget this step.

If we find that you did not properly clean up after yourself, well...
We will know who you are. We might not have money, but what we do have are a very particular set of skills. Skills we have acquired over a very long career. Skills that make us a nightmare for people like you. Ok, OpenShift skills, mostly, but still. So... yeah. We'll delete your Data Science Project. And we will grumble while doing it.
