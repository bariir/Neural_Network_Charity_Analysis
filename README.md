# Neural_Network_Charity_Analysis

## Purpose

The goal of this project is to analyze and help the foundation predict where to make investment. The team led by Beks will create a binary classifier that is capable of predicting if an applicant will be
successful if funded by the Alphabet Soup organization. The lead data scientist will be gathering datasets, preprocessing, fitting the neural network models to create a binary classifier systems.



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
![Train model with callbacks](/Resources/crypto_create_tradable_table.png)<br>

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
