#### `docs/api_reference.md`
API reference for the project:

```markdown
# API Reference

## RunAsh Class

### `load_data(file_path)`

Loads data from the specified file.

**Parameters**:
- `file_path` (str): The path to the data file.

**Returns**:
- DataFrame: The loaded data.

### `train_model(data)`

Trains a model using the provided data.

**Parameters**:
- `data` (DataFrame): The data to train the model on.

**Returns**:
- Model: The trained model.

### `predict(model, new_data)`

Makes predictions using the trained model on new data.

**Parameters**:
- `model` (Model): The trained model.
- `new_data` (DataFrame): The new data to make predictions on.

**Returns**:
- List: The predictions.

For a complete list of methods and their descriptions, refer to the source code and inline documentation.
