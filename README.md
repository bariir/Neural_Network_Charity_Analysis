# Neural_Network_Charity_Analysis

## Purpose

The goal of this project is to analyze and help the Alphabet Soup foundation predict where to make investment. The team led by Beks will create a binary classifier that is capable of predicting if an applicant will be
successful if funded by the Alphabet Soup organization. The team of data scientist will be gathering datasets, preprocessing the data, fitting the neural network models to create a binary classifier systems.



## Tools and Software 
- Anaconda, Jupyter Notebooks, Pandas, TensorFlow, Scikit-learn, etc. as well as Git Bash to commit changes into GitHub Repository.


# Results
Beks' goal is to analze the CSV file she received from Alphabet Soup's business team which contains more than 34K organizations that have received funding from Alphabet Soup over the years.
Beks's team ingests this source dataset and starts preprocessing of the data for a neural network including identifying feature variables, target variable, and those non-beneficial features that
will be excluded from the data frame. Also, the team determines number of unique values in each column and uses density plot to visualize value counts of columns such as APPLICATION_TYPE, and CLASSIFICATION 
that are candidate for binning. The ideal technique to use for this use case is neural network model.<br>


## Code Snippets 

- Preprocessing data for neural network model<br>
![Preprocessing data for neural network model](/Resources/nn_data_preprocessing.png)<br>

- Feature variables<br>
![Feature variables](/Resources/nn_feature_variables.png)<br>

- Target variable<br>
![Target variable](/Resources/nn_target_variable.png)<br>

- Identify columns to remove<br>
![Identify columns to remove](/Resources/nn_drop_non_needed_features.png)<br>

- Determine unique column values<br>
![Determine unique column values](/Resources/nn_determine_unique_column_values.png)<br>

- Vizualize values to replace<br>
![Vizualize values to replace](/Resources/nn_viz_determine_values_to_replace.png)<br>

- Generate catigorical variable lists<br>
![Generate catigorical variable lists](/Resources/nn_generate_categorical_variable_lists.png)<br>

- Create oneHotEncoder instance<br>
![Create oneHotEncoder](/Resources/nn_create_OneHotEncoder_instance.png)<br>

- Split preprocessed data and standardize it<br>
![Split preprocessed data and standardize](/Resources/nn_split_preprocessed_data_and_standardize.png)<br>

- Compile, train, and evaluate model<br>
![Compile, train, and evaluate model](/Resources/nn_compile_train_evaluate_model.png)<br>

- Checkpoint and saving the model<br>
![Checkpoint and saving the model](/Resources/nn_checkpoints_compile_create_callback_save_models_weights.png)<br>

- Train model with callbacks<br>
![Train model with callbacks](/Resources/nn_train_model_with_callbacks.png)<br>

- Evaluate model with test data<br>
![Evaluate model with test data](/Resources/nn_evaluate_model_with_test_data.png)<br>

- Export model to HDF5 file<br>
![Export model to HDF5 file](/Resources/nn_export_model_to_HDF5_file.png)<br>

- Optimize and drop more features<br>
![Optimize and drop more features](/Resources/nn_optimize_drop_more_features.png)<br>

- Optimize, compile, train and evaluate model<br>
![Optimize, compile, train and evaluate model](/Resources/nn_optimize_compile_train_evaluate_model.png)<br>

- Optimize, train with callbacks and export model to HDF5 file<br>
![Optimize, train with callbacks and export model to HDF5 file](/Resources/nn_optimize_train_with_callbacks_evaluate_and_export_model_to_HDF5_file.png)<br>



# Summary

The analaysis and neural network modeling done by Beks and her team of data scientists for Alphabet Soup Organization will enable the organziation to predict which applicants will be successful
if funded by Alphabet Soup. The team is using deep learning neural network model to create a binary classifier to predict which applicant will be successful and should be funded.

The end result will enable the decision making of Alphabet Soup Organization to either fund or not to fund certain applicants. The current models accuracy is 0.7016 or 70 percent. 
After the model optimization. I have not seen any improvement in accuracy score. In fact, I saw a diminished return of 0.5622. I have used multiple optionization techniques including the following.
1.	Dropped additional features such as AFFILIATION, ORGANIZATION, USE_CASE
2.	Replaced the number of count types that were less than 10000
3.	Added third addition hidden layers
4.	Changed activation function for the hidden layer from relu to tanh


## Links to images

Preprocessing data for neural network model: [nn_data_preprocessing.png](https://github.com/bariir/Neural_Network_Charity_Analysis/tree/main/Resources/nn_data_preprocessing.png?raw=true)<br>

Feature variables: [nn_feature_variables.png](https://github.com/bariir/Neural_Network_Charity_Analysis/tree/main/Resources/nn_feature_variables.png?raw=true)<br>

Target variable: [nn_target_variable.png](https://github.com/bariir/Neural_Network_Charity_Analysis/tree/main/Resources/nn_target_variable.png?raw=true)<br>

Identify columns to remove: [nn_drop_non_needed_features.png](https://github.com/bariir/Neural_Network_Charity_Analysis/tree/main/Resources/nn_drop_non_needed_features.png?raw=true)<br>

Determine unique column values: [nn_determine_unique_column_values.png](https://github.com/bariir/Neural_Network_Charity_Analysis/tree/main/Resources/nn_determine_unique_column_values.png?raw=true)<br>

Vizualize values to replace: [nn_viz_determine_values_to_replace.png](https://github.com/bariir/Neural_Network_Charity_Analysis/tree/main/Resources/nn_viz_determine_values_to_replace.png?raw=true)<br>

Generate catigorical variable lists: [nn_generate_categorical_variable_lists.png](https://github.com/bariir/Neural_Network_Charity_Analysis/tree/main/Resources/nn_generate_categorical_variable_lists.png?raw=true)<br>

Create oneHotEncoder instance: [nn_create_OneHotEncoder_instance.png](https://github.com/bariir/Neural_Network_Charity_Analysis/tree/main/Resources/nn_create_OneHotEncoder_instance.png?raw=true)<br>

Split preprocessed data and standardize: [nn_split_preprocessed_data_and_standardize.png](https://github.com/bariir/Neural_Network_Charity_Analysis/tree/main/Resources/nn_split_preprocessed_data_and_standardize.png?raw=true)<br>

Compile, train, and evaluate model: [nn_compile_train_evaluate_model.png](https://github.com/bariir/Neural_Network_Charity_Analysis/tree/main/Resources/nn_compile_train_evaluate_model.png?raw=true)<br>

Checkpoint and saving the model: [nn_checkpoints_compile_create_callback_save_models_weights.png](https://github.com/bariir/Neural_Network_Charity_Analysis/tree/main/Resources/nn_checkpoints_compile_create_callback_save_models_weights.png?raw=true)<br>

Train model with callbacks: [nn_train_model_with_callbacks.png](https://github.com/bariir/Neural_Network_Charity_Analysis/tree/main/Resources/nn_train_model_with_callbacks.png?raw=true)<br>

Evaluate model with test data: [nn_evaluate_model_with_test_data.png](https://github.com/bariir/Neural_Network_Charity_Analysis/tree/main/Resources/nn_evaluate_model_with_test_data.png?raw=true)<br>

Export model to HDF5 file: [nn_export_model_to_HDF5_file.png](https://github.com/bariir/Neural_Network_Charity_Analysis/tree/main/Resources/nn_export_model_to_HDF5_file.png?raw=true)<br>

Optimize and drop more features: [nn_optimize_drop_more_features.png](https://github.com/bariir/Neural_Network_Charity_Analysis/tree/main/Resources/nn_optimize_drop_more_features.png?raw=true)<br>

Optimize, compile, train and evaluate model: [nn_optimize_compile_train_evaluate_model.png](https://github.com/bariir/Neural_Network_Charity_Analysis/tree/main/Resources/nn_optimize_compile_train_evaluate_model.png?raw=true)<br>

Optimize, train with callbacks and export model to HDF5 file: [nn_optimize_train_with_callbacks_evaluate_and_export_model_to_HDF5_file.png](https://github.com/bariir/Neural_Network_Charity_Analysis/tree/main/Resources/nn_optimize_train_with_callbacks_evaluate_and_export_model_to_HDF5_file.png?raw=true)<br>


